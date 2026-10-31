<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnq1seb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnq1seb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:neural-network-fill-round" /></template>
