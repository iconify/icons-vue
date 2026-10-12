<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="gpws3vbqm"/><path class="ad3oim8dr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tree-ornament" /></template>
<style>
.ad3oim8dr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 13.5h.01M14 17h.01M9 17.5h.01");
}

.gpws3vbqm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.12 3.02l.29.63q.12.27.42.3l.68.08q.3.03.08.23l-.51.47q-.22.2-.16.49l.14.67q.06.3-.2.15l-.6-.34q-.26-.15-.52 0l-.6.34q-.26.15-.2-.15l.14-.67q.06-.29-.16-.49l-.51-.47q-.22-.2.08-.23l.68-.08q.3-.03.42-.3l.29-.63q.12-.27.24 0m.33 5.87l2.85 2.47q.45.39-.15.39h-.05q-.6 0-.18.42l2.91 2.91q.42.42-.18.42H16.6q-.6 0-.13.37l3.56 2.76q.47.37-.13.37H4.1q-.6 0-.13-.37l3.56-2.76q.47-.37-.13-.37H6.35q-.6 0-.18-.42l2.91-2.91q.42-.42-.18-.42h-.05q-.6 0-.15-.39l2.85-2.47q.45-.39.9 0M12 19v2.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
