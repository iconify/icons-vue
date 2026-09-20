<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y87ybjbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y87ybjbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:table-density-expanded" /></template>
