<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku8a62btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku8a62btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sword" /></template>
