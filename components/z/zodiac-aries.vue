<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-_oh8f1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-_oh8f1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:zodiac-aries" /></template>
