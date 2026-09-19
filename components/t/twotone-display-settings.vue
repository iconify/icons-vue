<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7rn8vskk"/><path class="t7lxhzbse"/><path class="qsv5997ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-display-settings" /></template>
<style>
.i7rn8vskk {
  fill: currentColor;
  d: path("M4 17h16V5H4zm14-3.25h-8v-1.5h8zM15 7h1.5v1.25H18v1.5h-1.5V11H15zM6 8.25h8v1.5H6zm0 4h1.5V11H9v4H7.5v-1.25H6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.qsv5997ug {
  fill: currentColor;
  d: path("M6 8.25h8v1.5H6zm10.5 1.5H18v-1.5h-1.5V7H15v4h1.5zm-6.5 2.5h8v1.5h-8zM7.5 15H9v-4H7.5v1.25H6v1.5h1.5z");
}

.t7lxhzbse {
  fill: currentColor;
  d: path("M20 3H4c-1.11 0-2 .89-2 2v12a2 2 0 0 0 2 2h4v2h8v-2h4c1.1 0 2-.9 2-2V5a2 2 0 0 0-2-2m0 14H4V5h16z");
}

</style>
