<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7d1ypbjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7d1ypbjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:search-ai-2-fill" /></template>
