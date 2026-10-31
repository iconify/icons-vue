<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy_rklbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy_rklbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:unfold-more-horizontal-fill-round" /></template>
