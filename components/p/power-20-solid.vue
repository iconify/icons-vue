<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fob5qsb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fob5qsb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:power-20-solid" /></template>
