<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-rtxebhr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-rtxebhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:socket-x" /></template>
