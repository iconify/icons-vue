<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hq-svrwqc"/><path class="zcgujg6ir"/><path class="g1ki__b_w"/><path class="x7d7t7bvx"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:scroll-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g1ki__b_w {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.188 14.269H9.605a.915.915 0 0 0-.911.93v1.087c.02.504.446.93.95.93h.562v-.93h-.562v-1.067h.31c.95 0 1.668.892 1.668 1.842c0 .854-.776 1.92-2.056 1.843c-1.144-.078-1.764-1.086-1.764-1.843v-9.25a.77.77 0 0 0-.757-.756H6.29v.95h.562v9.076c-.038 1.842 1.32 2.773 2.715 2.773l7.641.02A2.793 2.793 0 0 0 20 17.08c-.02-1.571-1.26-2.812-2.812-2.812m1.842 2.85a1.856 1.856 0 0 1-1.842 1.785l-5.314-.02a2.75 2.75 0 0 0 .68-1.823c0-1.085-.64-1.842-.64-1.842h5.293c1.009 0 1.843.834 1.843 1.842zM15.15 8.16H9.43v-.95h5.72c.253 0 .466.213.466.465c0 .271-.194.485-.465.485");
}

.hq-svrwqc {
  fill: var(--svg-color--101010, #101010);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.x7d7t7bvx {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.15 12.62H9.43v-.95h5.72c.253 0 .466.214.466.466c0 .271-.194.485-.465.485m1.009-2.231H9.43v-.95h6.73c.251 0 .465.213.465.465a.476.476 0 0 1-.466.485");
}

.zcgujg6ir {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.997 10.197c-.62-.582-1.047-1.339-1.047-2.23v-.098c.058-1.512 1.3-2.753 2.812-2.792h9.677c.253.02.447.194.447.446v8.203c.213.039.33.078.542.136c.175.058.408.194.408.194V5.523a1.42 1.42 0 0 0-1.416-1.396H7.762A3.833 3.833 0 0 0 4 7.967c0 1.221.562 2.268 1.454 2.986c.059.058.117.116.291.116c.291 0 .485-.233.466-.465c0-.213-.078-.291-.214-.407");
}

</style>
