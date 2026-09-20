<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-cms5byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i-cms5byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:trophy-fill" /></template>
