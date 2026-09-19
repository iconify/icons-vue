<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8yu3ealr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="l8yu3ealr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:polygon-hole-o" /></template>
