<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-fkjp1yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-fkjp1yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:truck-fast-round" /></template>
