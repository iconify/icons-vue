<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dne2lqbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dne2lqbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-3-bold" /></template>
