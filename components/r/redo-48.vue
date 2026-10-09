<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ooff228am.css';
import '../../css/d/d0qdug7jo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ooff228am"/><path class="d0qdug7jo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:redo-48" /></template>
