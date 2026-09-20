<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv1rs9bcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv1rs9bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:search-ai-line" /></template>
