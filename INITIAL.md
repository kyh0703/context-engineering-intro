## FEATURE:

xyflow를 사용해서 ansible을 시각화하는 기능을 구현하고 싶습니다. 이 기능은 Ansible 플레이북의 실행 흐름을 시각적으로 표현하여 사용자가 작업의 진행 상황과 의존성을 쉽게 이해할 수 있도록 합니다. 앤서블은 자동화된 IT 작업을 관리하는 도구로, 플레이북은 작업의 집합을 정의합니다. 앤서블 플로우를 구현하기 위해서는 사용자 서버에 설치된 엔서블 플로우 에이전트와 통신하여 플레이북의 실행 상태를 가져오고, 이를 리액트 플로우 컴포넌트에 전달하여 시각적으로 표현해야 합니다. 이 기능은 사용자가 플레이북의 각 작업이 어떻게 연결되어 있는지, 어떤 작업이 완료되었는지, 어떤 작업이 대기 중인지 등을 한눈에 볼 수 있도록 도와줍니다.

## EXAMPLES:

예제에서는 코드의 구조와 사용 방법을 이해하는 데 도움이 되는 파일들이 포함되어 있습니다.

- examples/template.ts - use this as a template to create the javascript code

이 예제들을 직접적으로 복사하지 마세요. 이들은 다른 프로젝트를 위한 것입니다. 하지만 이를 참고하여 모범 사례를 따르고 영감을 얻으세요

## DOCUMENTATION:

- https://reactflow.dev/api-reference

## OTHER CONSIDERATIONS:

- Include the project structure in the README.
