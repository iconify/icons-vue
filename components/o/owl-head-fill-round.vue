<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o89xpng8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o89xpng8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:owl-head-fill-round" /></template>
