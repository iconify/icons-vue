<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2atpgb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p2atpgb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:slider" /></template>
