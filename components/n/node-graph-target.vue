<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oer3upb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oer3upb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:node-graph-target" /></template>
