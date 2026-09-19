<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8cdtrbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f8cdtrbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:shapes-stroke-16" /></template>
