<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywp2qzbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywp2qzbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:square-arrow-up" /></template>
