<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6u8dutfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6u8dutfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:summarize-fill-round" /></template>
