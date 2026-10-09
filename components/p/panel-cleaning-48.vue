<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6e1f0btl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w6e1f0btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-cleaning-48" /></template>
