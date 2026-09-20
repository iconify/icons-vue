<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fox_q4z8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fox_q4z8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:redis" /></template>
