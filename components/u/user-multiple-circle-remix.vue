<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1y_909lf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y1y_909lf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:user-multiple-circle-remix" /></template>
