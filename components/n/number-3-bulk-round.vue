<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc8t9bblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dc8t9bblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-3-bulk-round" /></template>
