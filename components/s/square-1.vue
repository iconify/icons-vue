<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugx8g_87f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugx8g_87f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:square-1" /></template>
