<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9691i5gu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s9691i5gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:tilt" /></template>
