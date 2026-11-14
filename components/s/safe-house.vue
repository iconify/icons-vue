<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkhsz_bev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:safe-house" /></template>
<style>
.rkhsz_bev {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143L9.81 4.132q2.19-1.866 4.38 0l5.875 5.011q1.185 1.011 1.185 2.568v6.164q0 3.375-3.375 3.375H6.125q-3.375 0-3.375-3.375v-6.164q0-1.557 1.185-2.568m7.315 2.607h1.5V11q0-.75-.75-.75t-.75.75zm3 .2V11q0-2.25-2.25-2.25T9.75 11v.877q-1.5.437-1.5 2.373v1.5q0 2.5 2.5 2.5h2.5q1.036 0 1.768-.732t.732-1.768v-1.5q0-1.036-.732-1.768q-.35-.349-.768-.532");
}

</style>
