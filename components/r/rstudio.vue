<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppon23dld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ppon23dld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:rstudio" /></template>
