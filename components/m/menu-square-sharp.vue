<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hu6vpmn5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu6vpmn5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:menu-square-sharp" /></template>
