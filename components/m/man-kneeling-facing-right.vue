<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw9z_x7cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rw9z_x7cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:man-kneeling-facing-right" /></template>
