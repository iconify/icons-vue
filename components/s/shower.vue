<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3e-2qm4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d3e-2qm4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:shower" /></template>
