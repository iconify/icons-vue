<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjks_m-az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjks_m-az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:tivo" /></template>
