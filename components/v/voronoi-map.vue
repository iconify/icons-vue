<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw5iff9jp.css';
import '../../css/g/gsktsac_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="nw5iff9jp"/><path class="gsktsac_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:voronoi-map" /></template>
