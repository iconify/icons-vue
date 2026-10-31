<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq6l0acvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq6l0acvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ratio-3-2-fill-round" /></template>
