<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys5xo3bgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ys5xo3bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:trending-content" /></template>
