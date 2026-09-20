<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7g2f1bee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7g2f1bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:monitor" /></template>
