<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="g8wwzeqiw"/><path clip-rule="evenodd" class="rfnbodb8g"/><path class="zd0cs_bkv"/><path clip-rule="evenodd" class="mf7jrn0_x"/><path clip-rule="evenodd" class="f6-he1bmn"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:next-track-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f6-he1bmn {
  fill-rule: evenodd;
  d: path("M15.5 4a1 1 0 0 1 1 1v10a1 1 0 1 1-2 0V5a1 1 0 0 1 1-1");
}

.g8wwzeqiw {
  d: path("M9.863 9.318a1 1 0 0 1 0 1.364l-4.632 4.963c-.62.664-1.731.226-1.731-.682V5.037c0-.908 1.112-1.346 1.731-.682z");
}

.mf7jrn0_x {
  fill-rule: evenodd;
  d: path("M12.764 10L10.5 7.574v4.852zm2.1.682a1 1 0 0 0 0-1.364L10.23 4.355c-.62-.664-1.731-.226-1.731.682v9.926c0 .908 1.112 1.346 1.731.682z");
}

.rfnbodb8g {
  fill-rule: evenodd;
  d: path("M7.764 10L5.5 7.574v4.852zm2.1.682a1 1 0 0 0 0-1.364L5.23 4.355c-.62-.664-1.731-.226-1.731.682v9.926c0 .908 1.112 1.346 1.731.682z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.zd0cs_bkv {
  d: path("M14.863 9.318a1 1 0 0 1 0 1.364l-4.632 4.963c-.62.664-1.731.226-1.731-.682V5.037c0-.908 1.112-1.346 1.731-.682z");
}

</style>
