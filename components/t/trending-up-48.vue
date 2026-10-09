<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/infdtvbxp.css';
import '../../css/x/xa4y2gv4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="infdtvbxp"/><path class="xa4y2gv4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trending-up-48" /></template>
