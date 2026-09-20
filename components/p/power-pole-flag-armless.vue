<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgj3sr5dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mgj3sr5dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:power-pole-flag-armless" /></template>
