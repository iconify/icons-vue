<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1gl7fbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1gl7fbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:presentation-audience" /></template>
