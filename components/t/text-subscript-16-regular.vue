<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fkapty1fg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-subscript-16-regular" /></template>
<style>
.fkapty1fg {
  fill: currentColor;
  d: path("M2.168 3.126a.5.5 0 0 1 .706.042L6.5 7.248l3.626-4.08a.5.5 0 0 1 .748.664L7.169 8l2.848 3.204A3 3 0 0 0 10 11.5c0 .474.22.896.562 1.17a4 4 0 0 0-.186.314a.5.5 0 0 1-.25-.152L6.5 8.752l-3.626 4.08a.5.5 0 1 1-.748-.664L5.831 8L2.126 3.832a.5.5 0 0 1 .042-.706M12 11.5a.5.5 0 0 1 1 0c0 .259-.082.391-.19.499c-.1.101-.206.168-.35.259q-.104.064-.24.156C11.357 13 11 13.77 11 14.5a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 0-1h-1.394c.11-.252.316-.515.675-.758q.053-.036.129-.083c.174-.11.421-.267.607-.452c.283-.283.483-.666.483-1.207a1.5 1.5 0 0 0-3 0a.5.5 0 0 0 1 0");
}

</style>
