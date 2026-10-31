<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxp5dfuyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxp5dfuyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-bulk-round" /></template>
