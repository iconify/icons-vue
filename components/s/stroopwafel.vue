<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znxl5ob6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="znxl5ob6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:stroopwafel" /></template>
