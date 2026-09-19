<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci4-8k9hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ci4-8k9hh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:search-propertie" /></template>
