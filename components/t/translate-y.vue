<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpnll0i1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="zpnll0i1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:translate-y" /></template>
