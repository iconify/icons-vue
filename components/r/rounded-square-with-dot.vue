<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/og5zj6tba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="og5zj6tba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rounded-square-with-dot" /></template>
