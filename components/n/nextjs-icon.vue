<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGrDou6dwg" x1="55.633%" x2="83.228%" y1="56.385%" y2="96.08%"><stop offset="0%" class="vc--wpv5i"/><stop offset="100%" class="stui2mbih"/></linearGradient><linearGradient id="SVG9onTObtB" x1="50%" x2="49.953%" y1="0%" y2="73.438%"><stop offset="0%" class="vc--wpv5i"/><stop offset="100%" class="stui2mbih"/></linearGradient><circle id="SVGN5eQqeMK" class="ugn0xccey"/></defs><mask id="SVGMX2wGdvm" class="n1mjunbsu"><use href="#SVGN5eQqeMK"/></mask><g mask="url(#SVGMX2wGdvm)"><circle class="ugn0xccey"/><path fill="url(#SVGrDou6dwg)" class="xyujm1bwm"/><path fill="url(#SVG9onTObtB)" class="zptc8jici"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:nextjs-icon" /></template>
<style>
.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.ugn0xccey {
  cx: 128px;
  cy: 128px;
  r: 128px;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.xyujm1bwm {
  d: path("M212.634 224.028L98.335 76.8H76.8v102.357h17.228V98.68L199.11 234.446a128 128 0 0 0 13.524-10.418");
}

.zptc8jici {
  d: path("M163.556 76.8h17.067v102.4h-17.067z");
}

</style>
