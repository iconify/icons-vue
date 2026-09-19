<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="e_bv6ubgm"/><path class="cjmbr3bcs"/><g class="y16l70baz"><circle class="yj94e4bca"/><path class="lufrptbem"/><circle class="ls1yo1gbk"/><path class="n9so4db3l"/><circle class="r_w28qzwq"/><circle class="x2stddcav"/><circle class="hqsly9zby"/><circle class="sek9l58ct"/></g><g class="cm1o77xew"><path class="o0_6imo2c"/><circle class="lvjz7-bia"/><circle class="fx05f8yqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:waning-crescent-moon" /></template>
<style>
.cjmbr3bcs {
  fill: var(--svg-color--ffe8a6, #ffe8a6);
  d: path("M15 32c0-16.6 7.6-30 17-30C15.4 2 2 15.4 2 32s13.4 30 30 30c-9.4 0-17-13.4-17-30");
}

.cm1o77xew {
  fill: var(--svg-color--f4dc9f, #f4dc9f);
}

.e_bv6ubgm {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M32 2c-9.4 0-17 13.4-17 30s7.6 30 17 30c16.6 0 30-13.4 30-30S48.6 2 32 2");
}

.fx05f8yqh {
  cx: 15px;
  cy: 15.7px;
  r: 2px;
}

.hqsly9zby {
  cx: 25px;
  cy: 29.9px;
  r: 3px;
}

.ls1yo1gbk {
  cx: 37px;
  cy: 18.2px;
  r: 4px;
}

.lufrptbem {
  d: path("M24.2 41h-.4c.2-.6.4-1.3.4-2c0-3.3-2.7-6-6-6c-1.1 0-2.2.3-3.1.9c.1 3.9.7 7.6 1.6 10.9h.1l-.1.1c1.7 6.1 4.5 11 7.9 14c4.8-.2 8.5-4.2 8.5-9c.1-4.8-4-8.9-8.9-8.9M24 21.2c2.2 0 4-1.8 4-4c0-.6-.2-1.2-.4-1.8c.5.2 1 .3 1.6.3c2.8 0 5-2.2 5-5s-2.2-5-5-5s-5 2.2-5 5c0 1 .3 1.9.8 2.6c-.3-.1-.6-.1-.9-.1c-2.2 0-4 1.8-4 4c-.1 2.3 1.7 4 3.9 4");
}

.lvjz7-bia {
  cx: 8.1px;
  cy: 39px;
  r: 2px;
}

.n9so4db3l {
  d: path("M15.6 24c-.2 1.5-.4 3-.5 4.5c.6-.7 1-1.6 1-2.6c0-.7-.2-1.3-.5-1.9");
}

.o0_6imo2c {
  d: path("M15 33.9c-1.7 1-2.9 3-2.9 5.1c0 2.8 1.9 5.1 4.5 5.8c-.9-3.3-1.4-7-1.6-10.9M16.7 45c-1 1.4-1.5 3.2-1.5 5c0 5 4 9 9 9h.5c-3.5-2.9-6.3-7.9-8-14m-4.6-15.1c1.2 0 2.3-.5 3-1.4c.1-1.6.3-3.1.5-4.5c-.7-1.2-2-2.1-3.5-2.1c-2.2 0-4 1.8-4 4s1.8 4 4 4");
}

.r_w28qzwq {
  cx: 39px;
  cy: 9.2px;
  r: 2px;
}

.sek9l58ct {
  cx: 46px;
  cy: 52.6px;
  r: 4px;
}

.x2stddcav {
  cx: 52px;
  cy: 50px;
  r: 2px;
}

.y16l70baz {
  fill: var(--svg-color--464d51, #464d51);
}

.yj94e4bca {
  cx: 50px;
  cy: 35.2px;
  r: 7px;
}

</style>
