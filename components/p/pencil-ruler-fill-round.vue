<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc4s6ebod.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc4s6ebod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-ruler-fill-round" /></template>
