<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_mhsgprf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="h_mhsgprf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:plus-circle" /></template>
