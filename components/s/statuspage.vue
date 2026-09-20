<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":189};
const content = `<defs><linearGradient id="SVGXJp2PdIw" x1="50%" x2="50%" y1="82.799%" y2="-5.781%"><stop offset="0%" class="g_gp7lgqe"/><stop offset="82%" class="sav6x4bmf"/></linearGradient></defs><circle fill="url(#SVGXJp2PdIw)" class="aarkgfbhd"/><path class="d6mdabb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:statuspage" /></template>
<style>
.aarkgfbhd {
  cx: 128px;
  cy: 128.433px;
  r: 59.865px;
}

.d6mdabb-x {
  fill: var(--svg-color--2684ff, #2684ff);
  d: path("M1.616 59.255L33.8 97.374a6.86 6.86 0 0 0 9.744.72c52.118-46.73 116.657-46.73 168.912 0a6.86 6.86 0 0 0 9.744-.72l32.184-38.12a6.86 6.86 0 0 0-.79-9.64c-75.483-66.152-175.568-66.152-251.189 0a6.86 6.86 0 0 0-.789 9.64");
}

.g_gp7lgqe {
  stop-color: var(--svg-color--2684ff, #2684ff);
}

.sav6x4bmf {
  stop-color: var(--svg-color--0052cc, #0052cc);
}

</style>
