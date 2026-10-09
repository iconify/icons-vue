<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-6jetbog.css';
import '../../css/h/hbbf6bc_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h-6jetbog"/><path class="hbbf6bc_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:podium-20-bold" /></template>
