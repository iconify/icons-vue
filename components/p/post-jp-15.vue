<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yji4l09_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yji4l09_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:post-jp-15" /></template>
