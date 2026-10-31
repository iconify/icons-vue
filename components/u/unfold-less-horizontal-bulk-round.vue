<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a76k91d3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a76k91d3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:unfold-less-horizontal-bulk-round" /></template>
