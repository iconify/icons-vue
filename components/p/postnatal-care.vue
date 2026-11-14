<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r3zhx1bca"/><path class="zun85xc3m"/><path class="ibhwheuqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:postnatal-care" /></template>
<style>
.ibhwheuqd {
  fill: currentColor;
  d: path("M18 21.25s-3.5-2.25-3.5-4.5c0-1 .75-2 1.75-2c.75 0 1.5.5 1.75 1c.25-.5 1-1 1.75-1c1 0 1.75 1 1.75 2c0 2.25-3.5 4.5-3.5 4.5Z");
}

.r3zhx1bca {
  d: path("M11.752 17.661q-.177.149-.373.271t-.407.215t-.434.156t-.452.092q-.229.031-.46.028t-.459-.037q-.228-.035-.449-.102q-.222-.067-.431-.165l-3.625-1.69q-.145-.067-.282-.149t-.266-.176t-.248-.201t-.227-.224t-.203-.245t-.179-.264q-.083-.137-.152-.281t-.123-.294q-.055-.15-.095-.305q-.039-.154-.064-.312q-.024-.158-.033-.317q-.008-.16-.001-.319q.007-.16.029-.318t.061-.313q.038-.155.091-.306q.053-.15.12-.295l3.804-8.157q.067-.145.149-.282t.176-.266t.201-.248t.224-.227t.245-.203t.264-.179q.137-.083.281-.152t.294-.123q.15-.055.305-.095q.154-.039.312-.064q.158-.024.317-.033q.16-.008.319-.001q.16.007.318.029t.313.061q.155.038.306.091q.15.053.295.12l3.625 1.69q.145.067.282.149t.266.176t.248.201t.227.224t.203.245t.179.264t.152.281t.123.294t.095.305q.039.154.064.312q.024.158.033.317q.008.16.001.319q-.007.16-.029.318t-.061.313q-.038.155-.091.306q-.053.15-.12.295l-1.828 3.92");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zun85xc3m {
  d: path("M5.5 7.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm1 5.25c1.885-.236 4.213.417 5.731 1.957");
}

</style>
