<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7m5_-b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7m5_-b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:snowstorm-2-fill" /></template>
