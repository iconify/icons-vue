<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc3m5komh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc3m5komh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:soup-pot-line" /></template>
