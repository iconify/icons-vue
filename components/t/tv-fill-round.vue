<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzb_m2b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzb_m2b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tv-fill-round" /></template>
