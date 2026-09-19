<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aukm4obte.css';
import '../../css/r/r8ldhbbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="aukm4obte"/><path class="r8ldhbbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:search-address" /></template>
