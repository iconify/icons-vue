<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vj0zknb3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vj0zknb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:weather-lightning-rainy" /></template>
