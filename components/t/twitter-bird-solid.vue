<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf99i7bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf99i7bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:twitter-bird-solid" /></template>
