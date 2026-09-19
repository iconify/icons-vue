<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lua0b7fsf.css';
import '../../css/a/aukm4obte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="lua0b7fsf"/><path class="aukm4obte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:search-coord" /></template>
