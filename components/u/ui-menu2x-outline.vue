<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2ke1ngbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r2ke1ngbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ui-menu2x-outline" /></template>
