<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrqcf-bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mrqcf-bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ppe-goggles-outline" /></template>
