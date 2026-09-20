<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8df8ibqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8df8ibqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:weather-wind-flow-6-bold" /></template>
