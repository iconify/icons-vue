<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl7l21bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jl7l21bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:suitest" /></template>
