<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6f7qvxkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-scan" /></template>
<style>
.w6f7qvxkc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 4.25q0-3-3-3t-3 3t3 3t3-3m-8.915 6.396Q6.99 8.5 9.75 8.5h4.5q2.76 0 3.665 2.146l1.959 2.938q.026.039.047.081q.575 1.15-.148 2.054q-.625.781-1.773.781q-.795 0-1.367-.417l.6 3.997q.275.907-.289 1.564q-.519.606-1.444.606h-1.25q-1.725 0-1.75-1.7l-.481-3.852q-.009-.01-.019-.01t-.019.01L11.5 20.55q-.025 1.7-1.75 1.7H8.5q-.925 0-1.444-.606q-.564-.657-.289-1.564l.6-3.997Q6.795 16.5 6 16.5q-1.148 0-1.773-.781q-.723-.904-.148-2.054q.021-.042.047-.081zM10.75 10Q9 10 9 11.75t1.75 1.75q.952 0 1.386-.518q-.136.316-.136.768q0 1.5 1.5 1.5t1.5-1.5t-1.5-1.5q-.798 0-1.172.425q.172-.377.172-.925q0-1.75-1.75-1.75");
}

</style>
