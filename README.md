# Play Mode Saver

- UPM(Unity Package Manager) 형태로 작성

<br>

# How To Import

`[Window]` - `[Package Manager]` - `[+]` - `[Add package from git URL]` - `https://github.com/rito15/Unity-Play-Mode-Saver`

<br>

# Summary

- 등록한 컴포넌트들의 플레이 모드 내 변경사항을 플레이 모드가 종료되어도 유지시킵니다.

- 변경사항을 적용할 대상들은 `Play Mode Saver` 컴포넌트 내의 목록으로 관리됩니다.

- 유니티 에디터 내에서만 동작하며, 빌드 시 `Play Mode Saver` 컴포넌트는 자동으로 제거됩니다.

- 플레이 모드 내에서 `Play Mode Saver`를 수정한 사항도 플레이 모드가 종료되었을 때 유지됩니다.

<br>

# Preview

![2021_0313_PlayModeSaver](https://user-images.githubusercontent.com/42164422/111028409-cbac4880-8439-11eb-9812-1b2d303404d3.gif)

<br>

# How To Use

- 변경사항 유지를 원하는 컴포넌트에 우클릭 후, `Save Play Mode Changes`를 클릭합니다.

![image](https://user-images.githubusercontent.com/42164422/111024194-a6f7a700-8420-11eb-8019-b215be6b42e5.png)

<br>

- 자동으로 `Play Mode Saver` 컴포넌트가 해당 게임오브젝트에 추가되며,<br>
  `Components` 항목에서 목록을 확인할 수 있습니다.

![image](https://user-images.githubusercontent.com/42164422/111024242-f047f680-8420-11eb-8762-ac7190b30c35.png)

<br>

- 더이상 변경사항 유지를 원하지 않는 경우, 컴포넌트에 우클릭하여 `Don't Save Play Mode Changes`를 클릭하면 목록에서 제거됩니다.

![image](https://user-images.githubusercontent.com/42164422/111024315-7e23e180-8421-11eb-93aa-36f8898c16fa.png)

![image](https://user-images.githubusercontent.com/42164422/111024340-a01d6400-8421-11eb-9c7b-ec07c6b62746.png)

<br>

# Functions

![image](https://user-images.githubusercontent.com/42164422/111024364-ba574200-8421-11eb-9a71-f1f1671322c4.png)

<br>

## Options
- `Activated` : 클릭하여 On/Off할 수 있다. 버튼이 초록색인 상태에서만 변경사항 유지 기능이 동작하며, 빨간색인 경우 기능이 동작하지 않습니다.

- `Always On Top` : 클릭하여 On/Off할 수 있습니다. 버튼이 초록색인 경우, `Play Mode Saver` 컴포넌트는 인스펙터 내에서 항상 Transform 컴포넌트 다음에 위치합니다.

<br>

## Functions
- `Add All Components` : 해당 게임오브젝트 내의 모든 컴포넌트를 목록에 추가합니다.

- `Remove All Components` : 대상으로 등록된 모든 컴포넌트를 목록에서 제거합니다.

<br>

## Components
- 플레이 모드 변경사항 유지 대상으로 등록된 컴포넌트들의 목록

- 각 항목 우측의 `[ - ]` 버튼을 누를 경우, 대상 항목을 목록에서 제거합니다.

<br>
