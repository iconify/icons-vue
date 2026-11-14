<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpe0n5zdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:transplanting-trowel" /></template>
<style>
.tpe0n5zdg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.355 7.112q5.313-3.288 9.382-4.814q.069-.026.142-.038t.146-.01q.074.003.146.02t.139.047q.068.031.128.074t.11.097t.089.117t.065.132q.048.127.048.263t-.048.263q-1.526 4.069-4.814 9.382q-.039.063-.09.117t-.11.097t-.127.074q-.067.03-.139.047t-.146.02t-.147-.01t-.142-.038t-.132-.064q-.074-.046-.135-.108L14 11.061l-1.604 1.604q.822 1.298-.477 2.597l-5.657 5.657q-1.59 1.591-3.181 0t0-3.181l5.657-5.657q1.299-1.299 2.597-.477L12.939 10L11.22 8.28q-.106-.105-.163-.243T11 7.75t.057-.287t.163-.243q.061-.062.135-.108");
}

</style>
