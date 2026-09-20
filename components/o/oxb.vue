<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="suneiwepo"/><path class="yjvjqb-ui"/><path class="qdfi2vb7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:oxb" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qdfi2vb7x {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.05 9.975c0-.126.099-.225.225-.225h3.375c.931 0 1.35.418 1.35 1.35c0 .414-.203.707-.473.891c.27.18.473.482.473.91c0 .791-.558 1.35-1.35 1.35h-3.375a.225.225 0 0 1 0-.45h3.375c.544 0 .9-.356.9-.9c0-.406-.315-.64-.689-.676h-3.586a.225.225 0 0 1 0-.45h3.366c.068-.004.135-.009.211 0c.36-.045.698-.284.698-.675c0-.693-.207-.9-.9-.9h-3.375a.225.225 0 0 1-.225-.225");
}

.suneiwepo {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.35 10.2H6.6a.9.9 0 0 1 .9.9v.45a.225.225 0 1 0 .45 0v-.45A1.35 1.35 0 0 0 6.6 9.75H4.35A1.35 1.35 0 0 0 3 11.1v.45a.225.225 0 1 0 .45 0v-.45c0-.495.405-.9.9-.9m-.9 2.25a.225.225 0 1 0-.45 0v.45a1.35 1.35 0 0 0 1.35 1.35H6.6a1.35 1.35 0 0 0 1.35-1.35v-.45a.225.225 0 1 0-.45 0v.45a.9.9 0 0 1-.9.9H4.35a.9.9 0 0 1-.9-.9zm5.909-2.623a.225.225 0 0 1 .315-.019l2.25 2.026a.225.225 0 0 1 0 .333l-2.25 2.025a.225.225 0 0 1-.297-.333L11.437 12l-2.06-1.858a.225.225 0 0 1-.018-.316");
}

.yjvjqb-ui {
  fill: var(--svg-color--27e9af, #27e9af);
  d: path("M14.647 9.83a.254.254 0 0 1-.018.338L12.739 12l-.288-.36l1.89-1.832c.09-.09.225-.076.306.023m0 4.339a.26.26 0 0 0-.018-.338L12.739 12l-.288.36l1.89 1.832c.09.09.225.076.306-.023");
}

</style>
