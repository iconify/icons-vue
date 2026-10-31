<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv32cr-lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv32cr-lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-fill-round" /></template>
