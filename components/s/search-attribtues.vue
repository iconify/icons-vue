<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aukm4obte.css';
import '../../css/u/uub_5lb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="aukm4obte"/><path class="uub_5lb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:search-attribtues" /></template>
