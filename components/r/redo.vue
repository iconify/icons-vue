<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kg4balcnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kg4balcnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:redo" /></template>
