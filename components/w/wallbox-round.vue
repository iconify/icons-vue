<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwi_xactj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwi_xactj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wallbox-round" /></template>
