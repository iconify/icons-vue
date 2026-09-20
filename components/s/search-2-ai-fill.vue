<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpmobdbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpmobdbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:search-2-ai-fill" /></template>
