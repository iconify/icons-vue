<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4yvbibxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="q4yvbibxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:rain-wind" /></template>
