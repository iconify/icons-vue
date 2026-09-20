<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww-nxl0ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ww-nxl0ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:manhole-drain" /></template>
