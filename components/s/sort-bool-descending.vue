<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhdbi7b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhdbi7b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-bool-descending" /></template>
