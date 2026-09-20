<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evo-p5yty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evo-p5yty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:speedypage" /></template>
