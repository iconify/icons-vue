<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyogtrxua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":517.4,"height":517.4,"left":74.1,"top":22.2};
const content = `<path class="cyogtrxua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:sparkyfitness" /></template>
