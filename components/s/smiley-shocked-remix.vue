<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulcef3b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ulcef3b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:smiley-shocked-remix" /></template>
