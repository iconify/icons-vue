<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajnm6ob_j.css';
import '../../css/c/cscweibfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ajnm6ob_j"/><path class="cscweibfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-control" /></template>
