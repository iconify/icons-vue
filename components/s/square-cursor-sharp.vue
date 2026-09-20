<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-des9g1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-des9g1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square-cursor-sharp" /></template>
