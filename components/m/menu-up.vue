<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whztoynct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="whztoynct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:menu-up" /></template>
