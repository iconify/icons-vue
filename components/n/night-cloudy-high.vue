<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-behhx3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="e-behhx3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-cloudy-high" /></template>
