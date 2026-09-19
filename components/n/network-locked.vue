<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coghedhns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":456};
const content = `<path class="coghedhns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:network-locked" /></template>
