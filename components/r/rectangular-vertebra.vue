<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvq76tm2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mvq76tm2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:rectangular-vertebra" /></template>
