<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc4novbpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vc4novbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:sortable" /></template>
