<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="r1mb6vbfi"/><path class="jw_j0qt_b"/><path class="s7zz392-y"/><path class="j4s4fsbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:outbox-tray" /></template>
<style>
.j4s4fsbti {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M27.435 8.511L19.572.648a2.23 2.23 0 0 0-3.145 0L8.564 8.511C7.7 9.377 7.993 10 9.216 10H14v6a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2v-6h4.784c1.223 0 1.516-.623.651-1.489");
}

.jw_j0qt_b {
  fill: var(--svg-color--662113, #662113);
  d: path("M25 20a7 7 0 1 1-14 0z");
}

.r1mb6vbfi {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4v-9c0-2.209.791-3 3-3h30c2.209 0 3 .791 3 3z");
}

.s7zz392-y {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M4 36h28a4 4 0 0 0 4-4H0a4 4 0 0 0 4 4");
}

</style>
