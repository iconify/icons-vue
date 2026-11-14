<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc0qlt68p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pansy" /></template>
<style>
.hc0qlt68p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 3.954q-.708-1.017-2.028-1.547q-2.371-.952-4.404.597T3.824 7.091q.132 1.161.691 2.012q-1.247.378-2.086 1.872q-1.573 2.804.957 4.787q1.946 1.525 3.784.577q.328 1.23 1.294 2.197Q9.929 20 12 20t3.536-1.464q.966-.967 1.294-2.197q1.838.948 3.784-.577q2.53-1.983.957-4.787q-.839-1.494-2.086-1.872q.559-.851.691-2.012q.288-2.539-1.744-4.087q-2.033-1.549-4.404-.597q-1.32.53-2.028 1.547M9.75 11.5q0-2.25 2.25-2.25t2.25 2.25T12 13.75T9.75 11.5");
}

</style>
