<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxwld8isk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxwld8isk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:prompt-fill-round" /></template>
