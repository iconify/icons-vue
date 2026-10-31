<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtx1i4byc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtx1i4byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-close-round" /></template>
