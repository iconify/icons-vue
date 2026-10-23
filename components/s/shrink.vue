<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggis7yklh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggis7yklh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:shrink" /></template>
