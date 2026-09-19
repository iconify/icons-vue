<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1yx-1y0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="c1yx-1y0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:times-circle" /></template>
