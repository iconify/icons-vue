<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd4w9bbse.css';
import '../../css/k/k-gdp-2hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vd4w9bbse"/><path class="k-gdp-2hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:pnpm" /></template>
