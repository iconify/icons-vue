<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnq8kx7dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="rnq8kx7dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-sleet" /></template>
