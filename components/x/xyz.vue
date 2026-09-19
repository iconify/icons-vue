<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q50k_sb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="q50k_sb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:xyz" /></template>
