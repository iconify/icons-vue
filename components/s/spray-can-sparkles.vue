<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y28g32bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="y28g32bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:spray-can-sparkles" /></template>
