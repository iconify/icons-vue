<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dztpopbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="dztpopbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:tray-growth-chart-26" /></template>
