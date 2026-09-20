<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsc84_2my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsc84_2my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square-scissors-sharp" /></template>
