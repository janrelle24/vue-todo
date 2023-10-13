<template>
  <div>
    <div>
      <input type="text" placeholder="Add new Todo">
    </div>
    <div>
      <div>
        <span class="active" id="all">All</span>
        <span id="peding">Pending</span>
        <span id="completed">Completed</span>
      </div>
      <button class="clear-btn">Clear All</button>
    </div>
    <ul class="task-box"></ul>
  </div>
</template>