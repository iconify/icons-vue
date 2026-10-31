<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ija5sfmth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ija5sfmth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shirt-bulk-round" /></template>
