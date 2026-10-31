<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyt1u30bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyt1u30bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:soccer-ball-round" /></template>
