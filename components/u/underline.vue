<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtgyo3bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtgyo3bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:underline" /></template>
