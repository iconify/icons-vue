<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="d3rl-bc2s"/><path class="twj21kyfw"/><path class="nr-69h1tp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rmrk-background" /></template>
<style>
.d3rl-bc2s {
  fill: var(--svg-color--e92e88, #e92e88);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.nr-69h1tp {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 12V9.708a.307.307 0 0 0-.312-.309H4.53a.31.31 0 0 0-.308.309V12H4v.747h.223v1.545a.31.31 0 0 0 .312.308h15.153a.31.31 0 0 0 .312-.308v-1.55h-.175V12zm-.594.74v1.266H4.847v-1.263h-.253V12h.25V9.986h14.562V12h-.171v.743h.174v-.004z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.twj21kyfw {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.235 12.743h-.208c-.082-.186-.205-.32-.402-.372c.182-.044.454-.193.54-.371h.207a1.19 1.19 0 0 0-.137-1.126c-.186-.223-.502-.36-.988-.36H5.709V12h-.246v.743h.246v.743h.743v-.743h.546c.237 0 .323.2.468.535l.089.204h.977a12 12 0 0 1-.197-.49zm-1.783-1.486h.743c.16 0 .308.212.308.371c0 .16-.149.372-.312.372h-.74zm8.585 1.486h.208l.122.297c.056.149.123.312.179.442h-.981l-.09-.204c-.14-.335-.226-.535-.464-.535h-.501v.743h-.743v-.743h-.245V12h.245v-1.486h1.49c.642 0 1.2.33 1.188 1.01c0 .097-.022.387-.06.476h-.21c-.123.252-.287.308-.54.371c.201.052.324.186.402.372m-.833-1.486h-.694V12h.694c.16 0 .309-.212.309-.372s-.149-.371-.309-.371m4.287 1.549l-.219-.063l.539.743H17.76l-.528-.743h.216l-.286-.383l-.376.383h-.304v.743h-.743v-.743h.226V12h-.226v-1.486h.743v1.174l1.159-1.174h1.14l-1.26 1.3l.105.186h.22zm-7.726-1.538l.334-.754h1.096v1.356h-.171v.873h.17v.743h-.787v-.743h-.17v-.873h-.123l-.375.873h.208l-.286.743h-.327l-.298-.74h-.2l-.36-.873h-.053v.87h.168v.739h-.788v-.74h-.167v-.872h.167v-1.356h1.103l.335.754l.252.602h.023zm-1.17.397v.205h.092zm1.82 0l-.093.205h.093z");
}

</style>
