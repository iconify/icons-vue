<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk1dw34qb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="mk1dw34qb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:polygon" /></template>
