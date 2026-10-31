<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgk8ipbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgk8ipbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:merge-bulk-round" /></template>
