<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9o_g8hmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9o_g8hmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:soccer-ball" /></template>
