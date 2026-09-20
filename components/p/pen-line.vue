<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6_pfkl1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6_pfkl1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pen-line" /></template>
