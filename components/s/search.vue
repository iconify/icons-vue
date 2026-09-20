<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb7ja_97q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb7ja_97q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:search" /></template>
