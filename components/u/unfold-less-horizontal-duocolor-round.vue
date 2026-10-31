<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcfttybhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcfttybhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:unfold-less-horizontal-duocolor-round" /></template>
