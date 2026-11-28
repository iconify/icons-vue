<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/memn6_fup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="memn6_fup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:truck-clock" /></template>
