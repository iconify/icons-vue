<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p63rntbns"/><path class="n_sy2m0fq"/><path clip-rule="evenodd" class="w314yoqtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifier-slash-outline" /></template>
<style>
.n_sy2m0fq {
  fill: currentColor;
  d: path("M12.7373 9.20215C13.0302 8.90926 13.505 8.90926 13.7979 9.20215C14.0907 9.49504 14.0907 9.9698 13.7979 10.2627L10.2627 13.7979C9.9698 14.0907 9.49504 14.0907 9.20215 13.7979C8.90926 13.505 8.90926 13.0302 9.20215 12.7373L12.7373 9.20215Z");
}

.p63rntbns {
  fill: currentColor;
  d: path("M19.4697 19.4697C19.7626 19.1768 20.2374 19.1768 20.5303 19.4697L22.5303 21.4697C22.8232 21.7626 22.8232 22.2374 22.5303 22.5303C22.2374 22.8232 21.7626 22.8232 21.4697 22.5303L19.4697 20.5303C19.1768 20.2374 19.1768 19.7626 19.4697 19.4697Z");
}

.w314yoqtw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.5 1.25C17.1609 1.25 21.75 5.83908 21.75 11.5C21.75 17.1609 17.1609 21.75 11.5 21.75C5.83908 21.75 1.25 17.1609 1.25 11.5C1.25 5.83908 5.83908 1.25 11.5 1.25ZM11.5 2.75C6.66751 2.75 2.75 6.66751 2.75 11.5C2.75 16.3325 6.66751 20.25 11.5 20.25C16.3325 20.25 20.25 16.3325 20.25 11.5C20.25 6.66751 16.3325 2.75 11.5 2.75Z");
}

</style>
