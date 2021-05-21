using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class VariableFunction : MonoBehaviour
{
    // object를 키 입력에 따라 색 변화시키기
    void Update()
    {
        MeshRenderer renderer = gameObject.GetComponent<MeshRenderer>(); //객체의 MeshRenderer컴포넌트를 renderer 변수로 가리킨다

        if (Input.GetKeyDown(KeyCode.R)) //R을 입력했을 경우
        {
            renderer.material.color = Color.red; //MeshRenderer 컴포넌트에서 머티리얼의 색을 빨간색으로(R 입력 시 object가 빨간색으로 바뀜)
        }
        if (Input.GetKeyDown(KeyCode.G))
        {
            renderer.material.color = Color.green;
        }
        if (Input.GetKeyDown(KeyCode.B))
        {
            renderer.material.color = Color.blue;
        }
    }
}
