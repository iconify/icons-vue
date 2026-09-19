<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ds20ps-dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ds20ps-dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:search-country" /></template>
