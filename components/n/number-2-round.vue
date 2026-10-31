<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4-f04bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4-f04bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-2-round" /></template>
