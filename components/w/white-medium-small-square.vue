<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of_ijc5ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="of_ijc5ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:white-medium-small-square" /></template>
