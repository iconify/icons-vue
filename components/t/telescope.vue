<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="j78ub6b6q"/><path class="aoi34yxbc"/><path class="t1qzl95ym"/><path class="b2mv1kbsr"/><path class="nz2qv3v4s"/><path class="kbjb2547a"/><path class="yerc-ruah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:telescope" /></template>
<style>
.aoi34yxbc {
  fill: var(--svg-color--da2f47, #da2f47);
  d: path("M19.235 17.059a1.003 1.003 0 0 1-1.353.412L5.529 10.883a1.004 1.004 0 0 1-.412-1.353L7.94 4.235c.259-.485.868-.67 1.353-.412l12.353 6.588c.485.259.671.868.412 1.353z");
}

.b2mv1kbsr {
  fill: var(--svg-color--bb1a34, #bb1a34);
  d: path("m19.235 17.058l2.824-5.293l1.765.941L20.999 18z");
}

.j78ub6b6q {
  cx: 17px;
  cy: 20px;
  r: 3px;
  fill: var(--svg-color--9aaab4, #9aaab4);
}

.kbjb2547a {
  fill: var(--svg-color--292f33, #292f33);
  d: path("m8.294 7.824l1.882-3.53l-.881-.47v-.001L4.882 1.471a1.003 1.003 0 0 0-1.353.411L.706 7.177a1 1 0 0 0 .412 1.353l3.529 1.882l1.766.941l.47-.882zM23 25a2 2 0 0 1-2 2h-8a2 2 0 0 1 0-4h8a2 2 0 0 1 2 2");
}

.nz2qv3v4s {
  fill: var(--svg-color--9d0522, #9d0522);
  d: path("m28.942 22.235l2.823-5.294l3.53 1.882l-2.824 5.294z");
}

.t1qzl95ym {
  fill: var(--svg-color--da2f47, #da2f47);
  d: path("M31.177 22.293a1.004 1.004 0 0 1-1.354.412l-9.705-5.176a1.004 1.004 0 0 1-.412-1.354l1.882-3.529c.259-.485.868-.67 1.354-.412l9.705 5.176c.485.259.671.868.412 1.354z");
}

.yerc-ruah {
  fill: var(--svg-color--9aaab4, #9aaab4);
  d: path("m9.467 36l3.344-7.152c.468-1 .036-2.191-.965-2.658a1.997 1.997 0 0 0-2.658.965L5.052 36zm15.065 0h4.416l-4.137-8.846a1.997 1.997 0 0 0-2.658-.965a2 2 0 0 0-.965 2.658zM19 36v-8a2 2 0 0 0-4 0v8z");
}

</style>
