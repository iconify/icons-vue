<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz6k6rb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz6k6rb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:rocket" /></template>
