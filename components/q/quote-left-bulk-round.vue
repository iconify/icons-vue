<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg3t-zkoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg3t-zkoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:quote-left-bulk-round" /></template>
