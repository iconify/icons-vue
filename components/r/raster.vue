<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj0462s5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pj0462s5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:raster" /></template>
