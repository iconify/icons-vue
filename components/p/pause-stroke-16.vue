<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9htyfbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d9htyfbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:pause-stroke-16" /></template>
