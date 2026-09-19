<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpm90iwms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-settings-overscan" /></template>
<style>
.vpm90iwms {
  fill: currentColor;
  d: path("M12.01 7L10 9h4zM17 10v4l2-1.99zM7 10l-2 2.01L7 14zm7 5h-4l2.01 2zm6-11H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 14.01H4V5.99h16z");
}

</style>
