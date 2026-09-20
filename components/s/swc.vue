<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd47i7bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nd47i7bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:swc" /></template>
