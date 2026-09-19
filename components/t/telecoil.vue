<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp3oixb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp3oixb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:telecoil" /></template>
