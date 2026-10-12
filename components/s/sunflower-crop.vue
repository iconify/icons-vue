<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="cvsxsdb4v"/><circle class="oz-irh__q"/><path class="w7f2gdcsz"/><path class="of6ojcbzg"/><path class="i97s9rxmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sunflower-crop" /></template>
<style>
.cvsxsdb4v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.18 3.11l.39.73q.18.36.52.14l.7-.45q.34-.21.32.19l-.04.83q-.02.4.38.38l.83-.04q.4-.01.19.32l-.45.7q-.22.34.14.52l.73.39q.36.18 0 .36l-.73.39q-.36.18-.14.52l.45.7q.21.34-.19.32l-.83-.04q-.4-.02-.38.38l.04.83q.02.4-.32.19l-.7-.45q-.34-.22-.52.14l-.39.73q-.18.36-.36 0l-.39-.73q-.18-.36-.52-.14l-.7.45q-.33.21-.32-.19l.04-.83q.02-.4-.38-.38l-.83.04q-.4.02-.19-.32l.45-.7q.22-.34-.14-.52l-.73-.39q-.36-.18 0-.36l.73-.39q.36-.18.14-.52l-.45-.7q-.21-.33.19-.32l.83.04q.4.02.38-.38l-.04-.83q-.02-.4.32-.19l.7.45q.34.22.52-.14l.39-.73q.18-.36.36 0");
}

.i97s9rxmp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 11.25v10m-8.5-8v8m-3.75 0h18.5M15 17c.5-2 2-3 4.25-3c-.5 2-2 3-4.25 3");
}

.of6ojcbzg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 10h.01");
}

.oz-irh__q {
  cx: 15px;
  cy: 7px;
  r: 1.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w7f2gdcsz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.69 7.05l.32.51q.19.3.51.17l.57-.23q.32-.13.3.22l-.05.61q-.02.35.32.43l.59.15q.34.09.12.35l-.4.47q-.22.27 0 .54l.4.47q.22.26-.12.35l-.59.15q-.34.08-.32.43l.05.61q.02.35-.3.22l-.57-.23q-.32-.13-.51.17l-.32.51q-.19.3-.38 0l-.32-.51q-.19-.3-.51-.17l-.57.23q-.32.13-.3-.22l.05-.61q.02-.35-.32-.43l-.59-.15q-.34-.09-.12-.35l.4-.47q.22-.27 0-.54l-.4-.47q-.22-.26.12-.35l.59-.15q.34-.08.32-.43l-.05-.61q-.02-.35.3-.22l.57.23q.32.13.51-.17l.32-.51q.19-.3.38 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
