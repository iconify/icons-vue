<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp0yuxb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cp0yuxb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pencil-up" /></template>
