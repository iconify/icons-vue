<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9pxwi6fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9pxwi6fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:seal-line" /></template>
