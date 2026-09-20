<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx_0q1bgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx_0q1bgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:scroll-vertical-lock" /></template>
