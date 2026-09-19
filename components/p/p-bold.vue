<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_k-j67ku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="p_k-j67ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:p-bold" /></template>
