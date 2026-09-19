<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="jeunsn1yj"><path class="coott78px"/><path class="jp1p57tqt"/></g><path class="si2y7q9oh"/><path class="tgt0ysbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:top-hat" /></template>
<style>
.coott78px {
  d: path("M61.3 41.8c-3.2-7.5-15.3-1-29.3-1c-14.1 0-26.1-6.5-29.3 1C-1 49 10.5 61.9 32 61.9S65 49 61.3 41.8");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.jp1p57tqt {
  d: path("M32 1.9C18 2 7.9 8.1 9.3 11.5c3.8 12.5 5.2 23.8 4 36.3c12.6 3 24.9 2.8 37.4-.2c-1.2-12.5.2-23.6 4-36.1C56.1 8.1 46.1 2 32 1.9");
}

.si2y7q9oh {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M13.6 40.5c.2 2.5-1.1 7.3-1.1 7.3c11.6 11.1 27.4 11.1 39 0c0 0-1.1-4.7-1.1-7.3c-11.8 10.7-25 10.7-36.8 0");
}

.tgt0ysbzh {
  fill: var(--svg-color--656d72, #656d72);
  d: path("M55 10.4c0 4.7-10.3 8.4-23 8.4S9 15 9 10.4c0-4.7 10.3-8.5 23-8.5s23 3.8 23 8.5");
}

</style>
