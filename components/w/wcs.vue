<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw8x78bdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="qw8x78bdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:wcs" /></template>
