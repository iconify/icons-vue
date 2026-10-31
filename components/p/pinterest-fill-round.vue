<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1qk_lbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1qk_lbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pinterest-fill-round" /></template>
