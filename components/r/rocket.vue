<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2jx_csvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1632};
const content = `<path class="u2jx_csvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:rocket" /></template>
