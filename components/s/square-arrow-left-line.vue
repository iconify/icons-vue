<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml4doxj6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ml4doxj6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:square-arrow-left-line" /></template>
