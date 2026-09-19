<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="owu-y3bjq"/><g class="jeunsn1yj"><path class="pg6vtia1p"/><circle class="etosn2f5n"/></g><circle class="cbi3m-arz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:yin-yang" /></template>
<style>
.cbi3m-arz {
  cx: 21.4px;
  cy: 21.4px;
  r: 5.6px;
  fill: var(--svg-color--f5f5f5, #f5f5f5);
}

.etosn2f5n {
  cx: 42.6px;
  cy: 42.6px;
  r: 5.6px;
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.owu-y3bjq {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M53.2 10.8c11.7 11.7 11.7 30.7 0 42.4c-5.9 5.9-15.4 5.9-21.2 0S26.1 37.9 32 32s5.9-15.4 0-21.2s-15.4-5.9-21.2 0C22.5-.9 41.5-.9 53.2 10.8");
}

.pg6vtia1p {
  d: path("M10.8 53.2C-.9 41.5-.9 22.5 10.8 10.8c5.9-5.9 15.4-5.9 21.2 0c5.9 5.9 5.9 15.4 0 21.2s-5.9 15.4 0 21.2s15.4 5.9 21.2 0c-11.7 11.7-30.7 11.7-42.4 0");
}

</style>
