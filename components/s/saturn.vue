<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8l9c_b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8l9c_b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:saturn" /></template>
