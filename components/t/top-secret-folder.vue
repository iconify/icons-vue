<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj_etcdbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:top-secret-folder" /></template>
<style>
.zj_etcdbo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 7q0-2.75 2.75-2.75h4.5q.149 0 .287.057t.243.163l1.781 1.78H19q2.75 0 2.75 2.75v8q0 2.75-2.75 2.75H5q-2.75 0-2.75-2.75zm9 3.75h1.5v-.25q0-.75-.75-.75t-.75.75zm3 .497V10.5q0-2.25-2.25-2.25T9.75 10.5v.588q-1 .581-1 2.162v1q0 2.5 2.5 2.5h1.5q1.036 0 1.768-.732t.732-1.768v-1q0-1.036-.732-1.768q-.129-.129-.268-.235");
}

</style>
