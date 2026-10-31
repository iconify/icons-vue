<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm1d_swqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fm1d_swqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spoon-beside-table-knife-in-eaved-gabled-shelter" /></template>
