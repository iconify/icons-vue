<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh3x8xafe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh3x8xafe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mountain-bulk-round" /></template>
