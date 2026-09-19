<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vse78tblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":459,"height":512};
const content = `<path class="vse78tblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:neo4j" /></template>
