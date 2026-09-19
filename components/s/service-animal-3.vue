<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryqn2dhuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ryqn2dhuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:service-animal-3" /></template>
