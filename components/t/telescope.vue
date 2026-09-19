<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf4x2lbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mf4x2lbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:telescope" /></template>
