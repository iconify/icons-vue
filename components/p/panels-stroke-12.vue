<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tatr91rod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="tatr91rod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:panels-stroke-12" /></template>
