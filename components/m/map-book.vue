<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-06qbclg.css';
import '../../css/r/ryca0qb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="c-06qbclg"/><path class="ryca0qb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-book" /></template>
