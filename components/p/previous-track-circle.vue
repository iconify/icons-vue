<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path class="zlpxmnbao"/><path clip-rule="evenodd" class="xwdqv2bsf"/><path class="qyf-1n63u"/><path clip-rule="evenodd" class="a-mnc9dvl"/><path clip-rule="evenodd" class="enov0h9ru"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:previous-track-circle" /></template>
<style>
.a-mnc9dvl {
  fill-rule: evenodd;
  d: path("m10.236 13l2.264-2.426v4.852zm-2.1.682a1 1 0 0 1 0-1.364l4.633-4.963c.62-.664 1.731-.226 1.731.682v9.926c0 .908-1.112 1.346-1.731.682z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.enov0h9ru {
  fill-rule: evenodd;
  d: path("M7.5 7a1 1 0 0 0-1 1v10a1 1 0 1 0 2 0V8a1 1 0 0 0-1-1");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.qyf-1n63u {
  d: path("M8.137 12.318a1 1 0 0 0 0 1.364l4.632 4.963c.62.664 1.731.226 1.731-.682V8.037c0-.908-1.112-1.346-1.731-.682z");
}

.xwdqv2bsf {
  fill-rule: evenodd;
  d: path("m15.236 13l2.264-2.426v4.852zm-2.1.682a1 1 0 0 1 0-1.364l4.633-4.963c.62-.664 1.731-.226 1.731.682v9.926c0 .908-1.112 1.346-1.731.682z");
}

.zlpxmnbao {
  d: path("M13.137 12.318a1 1 0 0 0 0 1.364l4.632 4.963c.62.664 1.731.226 1.731-.682V8.037c0-.908-1.112-1.346-1.731-.682z");
}

</style>
