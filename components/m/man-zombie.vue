<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of_2nclse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="of_2nclse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:man-zombie" /></template>
