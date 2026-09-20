<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru29i1boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ru29i1boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:more-horizontal" /></template>
