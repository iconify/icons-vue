<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iywt5db8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iywt5db8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ruler-round" /></template>
