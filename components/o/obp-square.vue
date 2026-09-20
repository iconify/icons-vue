<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfdjb0b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="mfdjb0b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:obp-square" /></template>
