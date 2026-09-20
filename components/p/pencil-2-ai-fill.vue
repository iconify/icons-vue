<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eutmcdbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eutmcdbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pencil-2-ai-fill" /></template>
