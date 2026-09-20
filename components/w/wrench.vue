<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm79hrbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm79hrbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:wrench" /></template>
