<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0al58b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0al58b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:minus" /></template>
