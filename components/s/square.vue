<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0-q9nbjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0-q9nbjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square" /></template>
