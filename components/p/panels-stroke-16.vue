<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/psh001bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="psh001bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:panels-stroke-16" /></template>
