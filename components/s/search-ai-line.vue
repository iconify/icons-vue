<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmsbdoo2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmsbdoo2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:search-ai-line" /></template>
