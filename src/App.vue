
<template>
<body>
  <table id="course">
    <tr>
      <th>&nbsp;</th>
      <th>星期一</th>
      <th>星期二</th>
      <th>星期三</th>
      <th>星期四</th>
      <th>星期五</th>
      <th>星期六</th>
      <th>星期天</th>
    </tr>
    <tr>
      <th>
        <div>
          第一节
          <br />
          <span class="time">[8:00-9:50]</span>
        </div>
      </th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>
        <div>
          第二节
          <br />
          <span class="time">[8:00-9:50]</span>
        </div>
      </th>
      <td>
        <div>
          软件构造原理<br/>
          第5-7周
          <br />
          <span class="space">东区一教DQ402</span>
        </div>
      </td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>
        <div>
          第一节
          <br />
          <span class="time">[8:00-9:50]</span>
        </div>
      </th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <th>
        <div>
          第一节
          <br />
          <span class="time">[8:00-9:50]</span>
        </div>
      </th>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </table>
</body>
</template>

<script>
</script>

<style>
/* 表格 */
#course {
  width: 100%;
  border-collapse: collapse;
}
#course th {
  text-align: left;
  padding-top: 5px;
  padding-bottom: 4px;
  background-color: pink;
  color: #ffffff;
}
#course td,
#course th {
  font-size: 1em;
  border: 1px solid palevioletred;
  padding: 3px 7px 2px 7px;
}
#course tr {
   color: #8B5F65;
}

.time {
  color: #eeeee0;
  font-size: 0.8em;
}
.space {
  color: 	#CD8C95;
  font-size: 0.8em;
}
</style>
