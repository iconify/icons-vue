<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-2cu9-vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:physical-therapy-sharp" /></template>
<style>
.w-2cu9-vo {
  fill: currentColor;
  d: path("M15.423 15.385h-6.24q-.402 0-.659.254t-.312.569t.089.634t.541.462l5.417 2.14q.212.081.42.063q.21-.019.371-.144t.267-.308q.106-.184.106-.401zm-3.3-10.508Q13 5.754 13 7t-.877 2.123T10 10t-2.123-.877T7 7t.877-2.123T10 4t2.123.877m6.718 6.508q.475 0 .817.324t.342.799q0 .402-.229.704t-.606.425l-2.742.748h-7.24q-.83 0-1.41.58q-.58.581-.58 1.41q0 .508.307.92t.758.647l1.115.443H4v-3q0-1.671 1.165-2.836Q6.329 11.385 8 11.385z");
}

</style>
