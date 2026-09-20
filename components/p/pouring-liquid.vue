<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ngs907bkb"/><path class="itetuv41v"/><path class="eet-pzbdp"/><ellipse transform="rotate(-70.001 4.356 6.807)" class="bsv-9kbmw"/><path class="y4h2p2bdd"/><path class="q_4vb7b4d"/><path class="tegl9dbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:pouring-liquid" /></template>
<style>
.bsv-9kbmw {
  cx: 4.356px;
  cy: 6.807px;
  fill: var(--svg-color--d9dddc, #d9dddc);
  rx: 5.175px;
  ry: 1.882px;
}

.eet-pzbdp {
  fill: var(--svg-color--aeb3b2, #aeb3b2);
  d: path("M23.38 13.731c1.573-4.321 3.542-6.172 4.06-6.18c.313.311.632 2.995-.941 7.315s-3.542 6.172-4.06 6.18c-.314-.31-.632-2.994.941-7.315");
}

.itetuv41v {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.979 9.523a1 1 0 0 1-.286-.042l-9.25-2.767a1 1 0 0 1 .572-1.916l9.25 2.767a1 1 0 0 1-.286 1.958");
}

.ngs907bkb {
  fill: var(--svg-color--c4c9c8, #c4c9c8);
  d: path("M27.777 6.502c-.029-.011-.088-.027-.088-.027L5.633.801l-.002.007C4.478.512 2.674 2.698 1.55 5.786s-1.147 5.922-.073 6.436l-.002.007l20.543 9.831s.055.025.085.036c1.435.522 3.869-2.545 5.437-6.851c1.565-4.306 1.672-8.22.237-8.743");
}

.q_4vb7b4d {
  fill: var(--svg-color--c4c9c8, #c4c9c8);
  d: path("M22.439 21.047c-.313-.311-.632-2.995.941-7.315s3.542-6.172 4.06-6.18l.337-1.049c-1.435-.522-3.869 2.545-5.437 6.851c-1.567 4.306-1.674 8.22-.239 8.742z");
}

.tegl9dbvl {
  fill: var(--svg-color--bf6952, #bf6952);
  d: path("M24.111 19.935c2.294 1.097 3.683 3.48 4.68 5.735a.339.339 0 1 1-.63.249c-.418-1.153-.949-2.27-1.623-3.287c-.67-1.001-1.497-1.931-2.542-2.475c-.141-.07-.028-.297.115-.222");
}

.y4h2p2bdd {
  fill: var(--svg-color--a6373b, #a6373b);
  d: path("M30.9 33.036c-.408-3.986-1.164-8.323-3.954-11.455c-1.016-1.146-2.406-1.955-3.836-2.479L7.65 12.751c-.604-.291-1.019.628-.432.902a436 436 0 0 1 7.539 3.575c.429.198 8.365 4.047 8.446 4.077c4.077 2.279 4.686 7.323 4.867 11.732c-2.901.151-5.07.748-5.07 1.463c0 .828 2.91 1.5 6.5 1.5s6.5-.672 6.5-1.5c0-.717-2.184-1.316-5.1-1.464");
}

</style>
