<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bva1ywnrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bva1ywnrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:trash-solid" /></template>
