<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aukm4obte.css';
import '../../css/z/zu_0t47tj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="aukm4obte"/><path class="zu_0t47tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:search-home" /></template>
