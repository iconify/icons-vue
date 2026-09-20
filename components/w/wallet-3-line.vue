<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqx3i42jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqx3i42jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:wallet-3-line" /></template>
