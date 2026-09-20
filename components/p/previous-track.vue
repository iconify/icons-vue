<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="cmb7x4l_n"/><path clip-rule="evenodd" class="i6eu-229z"/><path class="j3enf4crm"/><path clip-rule="evenodd" class="wszww20lf"/><path clip-rule="evenodd" class="ho2b1cc0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:previous-track" /></template>
<style>
.cmb7x4l_n {
  d: path("M10.137 9.318a1 1 0 0 0 0 1.364l4.632 4.963c.62.664 1.731.226 1.731-.682V5.037c0-.908-1.112-1.346-1.731-.682z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ho2b1cc0b {
  fill-rule: evenodd;
  d: path("M4.5 4a1 1 0 0 0-1 1v10a1 1 0 1 0 2 0V5a1 1 0 0 0-1-1");
}

.i6eu-229z {
  fill-rule: evenodd;
  d: path("M12.236 10L14.5 7.574v4.852zm-2.1.682a1 1 0 0 1 0-1.364l4.633-4.963c.62-.664 1.731-.226 1.731.682v9.926c0 .908-1.112 1.346-1.731.682z");
}

.j3enf4crm {
  d: path("M5.137 9.318a1 1 0 0 0 0 1.364l4.632 4.963c.62.664 1.731.226 1.731-.682V5.037c0-.908-1.112-1.346-1.731-.682z");
}

.wszww20lf {
  fill-rule: evenodd;
  d: path("M7.236 10L9.5 7.574v4.852zm-2.1.682a1 1 0 0 1 0-1.364L9.77 4.355c.62-.664 1.731-.226 1.731.682v9.926c0 .908-1.112 1.346-1.731.682z");
}

</style>
