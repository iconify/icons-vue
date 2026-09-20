<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="qx4vxhbjx"/><path class="ogawhdbxr"/><circle class="tieb_sdfa"/><circle class="mcsilq5el"/><circle class="rh0m0lm3b"/><circle class="fec_atbaj"/><path class="w4brdnbnv"/><path class="hr1rdftci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:taxi" /></template>
<style>
.fec_atbaj {
  cx: 27px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.hr1rdftci {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M24 21h5.92a13 13 0 0 0-.156-1.5c-.395-2.5-.552-3.5-3.437-3.5H24zm-2-5h-5c-1.594 0-3.236 1.567-3.847 3.5c-.194.599-.353 1.088-.472 1.5H22z");
}

.mcsilq5el {
  cx: 10px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.ogawhdbxr {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M32.246 21h-.135l-.444-3c-.327-2.209-1.864-4-3.433-4H16.162c-1.569 0-3.574 1.791-4.478 4l-1.228 3H6.911c-2.073 0-4.104 1.791-4.538 4l-.588 3q0 .012-.002.021A1.995 1.995 0 0 0 0 30a2 2 0 0 0 2 2h30a4 4 0 0 0 4-4v-3c0-2.209-1.681-4-3.754-4");
}

.qx4vxhbjx {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M21.377 15.449c.089.816-.83 1.495-2.053 1.515s-2.095-.635-1.947-1.463l.356-2c.147-.829.938-1.5 1.767-1.5c.828 0 1.572.662 1.661 1.478z");
}

.rh0m0lm3b {
  cx: 27px;
  cy: 31px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

.tieb_sdfa {
  cx: 10px;
  cy: 31px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

.w4brdnbnv {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("m2.373 25l-.196 1H36v-1c0-.348-.055-.679-.133-1H2.702a4.8 4.8 0 0 0-.329 1");
}

</style>
