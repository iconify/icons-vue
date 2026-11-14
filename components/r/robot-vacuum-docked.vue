<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g2uflwmiu"/><path class="wrtbahbxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:robot-vacuum-docked" /></template>
<style>
.g2uflwmiu {
  d: path("M3 6.5a9 3.5 0 1 0 18 0a9 3.5 0 1 0-18 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wrtbahbxh {
  d: path("M3 6.5v3q0 .086.011.172t.033.171t.054.17t.075.17t.097.167q.054.084.118.166t.139.163q.074.081.159.16t.179.157t.199.153q.104.076.217.15q.114.074.237.145t.254.14t.272.136q.14.066.289.13q.148.063.304.124t.32.119t.335.112t.348.105t.361.099t.373.092t.384.085q.195.04.395.077q.199.037.404.069q.204.033.412.062t.419.054t.426.046t.431.038t.435.029t.438.021t.44.013t.442.004q.704 0 1.399-.043t1.366-.126q.67-.085 1.298-.208q.628-.124 1.199-.284m.276-.08q.403-.123.768-.262q.364-.139.686-.294t.597-.322t.499-.346q.224-.178.395-.366q.17-.187.286-.381q.115-.193.173-.391Q21 9.699 21 9.5v-3M11 19.75H2.5v-3.5H14M19.5 14l-4 4.75H18L16.75 22L21 17h-2.5Z");
}

</style>
