<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we9bqbb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="we9bqbb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:map-plus" /></template>
