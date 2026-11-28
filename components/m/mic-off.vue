<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-z8kcc9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-z8kcc9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:mic-off" /></template>
