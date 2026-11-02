<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q466almew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q466almew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:notion-fill" /></template>
