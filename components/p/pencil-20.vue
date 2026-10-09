<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azix1pzje.css';
import '../../css/a/ajjz77quj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="azix1pzje"/><path class="ajjz77quj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pencil-20" /></template>
