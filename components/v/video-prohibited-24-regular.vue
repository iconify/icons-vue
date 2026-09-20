<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1qc8qbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-prohibited-24-regular" /></template>
<style>
.i1qc8qbhh {
  fill: currentColor;
  d: path("M6.5 11a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m-2.248 8.809a4 4 0 0 0 5.557-5.557zM12.75 5A3.25 3.25 0 0 1 16 8.25v.312l3.258-2.25c1.16-.801 2.744.03 2.744 1.44v8.495c0 1.41-1.583 2.242-2.744 1.44L16 15.438v.313A3.25 3.25 0 0 1 12.75 19h-.249a6.5 6.5 0 0 0 .423-1.509A1.75 1.75 0 0 0 14.5 15.75v-7.5a1.75 1.75 0 0 0-1.75-1.75h-7.5A1.75 1.75 0 0 0 3.5 8.25v2.483A6.5 6.5 0 0 0 2 11.812V8.25A3.25 3.25 0 0 1 5.25 5zM6.5 12.5a4 4 0 0 0-3.309 6.248l5.557-5.557A4 4 0 0 0 6.5 12.5m14.002-4.748a.25.25 0 0 0-.393-.206L16 10.384v3.231l4.11 2.838a.25.25 0 0 0 .392-.206z");
}

</style>
