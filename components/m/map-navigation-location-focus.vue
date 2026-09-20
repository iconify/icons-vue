<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7ioqnsvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a7ioqnsvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:map-navigation-location-focus" /></template>
