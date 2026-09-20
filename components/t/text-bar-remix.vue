<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqe1w2mmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wqe1w2mmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:text-bar-remix" /></template>
