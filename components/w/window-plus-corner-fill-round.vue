<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7--8bbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7--8bbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-plus-corner-fill-round" /></template>
