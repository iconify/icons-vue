<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbed15bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:physical-therapy-rounded" /></template>
<style>
.hbed15bcf {
  fill: currentColor;
  d: path("M14.26 19.444q.211.081.42.063t.37-.144t.267-.308t.106-.401v-2.462q0-.348-.23-.577t-.577-.23H9.183q-.402 0-.659.253t-.312.57t.089.634t.541.462zm4.58-8.06q.476 0 .818.325q.342.324.342.799q0 .402-.229.704t-.606.425l-2.742.748h-7.24q-.83 0-1.41.58q-.58.581-.58 1.41q0 .508.307.92t.758.647l1.115.443H4.808q-.348 0-.578-.23T4 17.577v-2.193q0-1.67 1.165-2.835Q6.329 11.385 8 11.385zm-6.717-6.507Q13 5.754 13 7t-.877 2.123T10 10t-2.123-.877T7 7t.877-2.123T10 4t2.123.877");
}

</style>
