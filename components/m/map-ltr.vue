<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww8qfyb6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ww8qfyb6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:map-ltr" /></template>
