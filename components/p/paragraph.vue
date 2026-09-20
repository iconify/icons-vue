<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwa1keyih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bwa1keyih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:paragraph" /></template>
