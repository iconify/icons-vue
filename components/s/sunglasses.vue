<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw5dt7bmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vw5dt7bmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sunglasses" /></template>
