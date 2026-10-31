<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oouo4ab_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oouo4ab_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:satellite-dish-round" /></template>
