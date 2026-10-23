<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmfg-je0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmfg-je0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:plane-landing" /></template>
