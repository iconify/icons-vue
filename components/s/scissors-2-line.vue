<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l8suaobgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8suaobgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scissors-2-line" /></template>
