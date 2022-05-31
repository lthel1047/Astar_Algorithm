# Astar_Algorithm

A* 알고리즘을 공부하며 위키백과 및 다른 개발자들의 코드를 많이 참고 했습니다.  
공부하며 GUILayout을 이용해 유저의 편의를 생각해 사용해 보았습니다.  
처음 제대로 사용해봐서 공부하는데 사용하는데 어려움이 많았습니다.  

  '''

    void ReconstructionGrid(int windowId)
    {
        string value;

        GUIStyle textStyle = new GUIStyle("TextField");
        GUILayout.BeginVertical("box");
        GUILayout.Label("Size X : 2 ~ 100");
        GUILayout.BeginHorizontal();
        GUILayout.Label("Size X", GUILayout.MinWidth(50));
        value = GUILayout.TextField(grid.gridWorldSize.x.ToString(), textStyle, GUILayout.MinWidth(50));
        grid.gridWorldSize.x = int.Parse(value);
        GUILayout.EndHorizontal();
        GUILayout.Label("Size Y : 2 ~ 50");
        GUILayout.BeginHorizontal();
        GUILayout.Label("Size Y", GUILayout.MinWidth(50));
        value = GUILayout.TextField(grid.gridWorldSize.y.ToString(), textStyle, GUILayout.MinWidth(50));
        grid.gridWorldSize.y = int.Parse(value);
        GUILayout.EndHorizontal();
        GUILayout.EndVertical();
     }   
   '''
각종 GUI 버튼을 구현하였습니다.
