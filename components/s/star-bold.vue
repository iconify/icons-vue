<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rvd_l_cdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="rvd_l_cdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:star-bold" /></template>
