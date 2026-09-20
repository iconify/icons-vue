<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c9r5smbwx"/><path class="jcjmfmcsn"/><path class="pwircwb2l"/><path class="q7tmdybad"/><path class="yqzayebjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:mantl" /></template>
<style>
.c9r5smbwx {
  d: path("M256 128c0 70.692-57.308 128-128 128C57.308 256 0 198.692 0 128C0 57.308 57.308 0 128 0c70.692 0 128 57.308 128 128");
  fill: var(--svg-color--221f1f, #221F1F);
}

.jcjmfmcsn {
  d: path("M144.275 129.039c0-9.18-7.441-16.621-16.621-16.621c-.12 0-.228.032-.346.035v16.586h16.967z");
  fill: var(--svg-color--ffe000, #FFE000);
}

.pwircwb2l {
  d: path("M127.654 100.745c15.626 0 28.294 12.668 28.294 28.294h19.506c0-26.4-21.401-47.8-47.8-47.8c-.117 0-.23.017-.346.017v19.506c.116-.001.229-.017.346-.017");
  fill: var(--svg-color--ff9510, #FF9510);
}

.q7tmdybad {
  d: path("M127.654 68.418c33.48 0 60.62 27.141 60.62 60.62h19.139c0-44.049-35.71-79.758-79.76-79.758c-.116 0-.23.017-.345.017v19.14c.116-.002.229-.019.346-.019");
  fill: var(--svg-color--ff4b21, #FF4B21);
}

.yqzayebjh {
  d: path("M127.654 36.44c51.14 0 92.599 41.458 92.599 92.599h19.446c0-61.88-50.165-112.044-112.045-112.044c-.116 0-.23.008-.346.009v19.445c.116-.001.23-.01.346-.01");
  fill: var(--svg-color--ff0031, #FF0031);
}

</style>
