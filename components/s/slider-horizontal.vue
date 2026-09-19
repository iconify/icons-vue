<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll70l5bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll70l5bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:slider-horizontal" /></template>
