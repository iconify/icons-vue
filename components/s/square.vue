<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3g8599er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="l3g8599er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:square" /></template>
