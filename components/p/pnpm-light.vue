<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz6mnac-c.css';
import '../../css/k/k-gdp-2hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dz6mnac-c"/><path class="k-gdp-2hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:pnpm-light" /></template>
