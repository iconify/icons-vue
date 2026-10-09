<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1329qbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m1329qbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:parallelogram-48-bold" /></template>
