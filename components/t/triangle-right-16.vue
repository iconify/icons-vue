<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnv09c1ef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pnv09c1ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:triangle-right-16" /></template>
