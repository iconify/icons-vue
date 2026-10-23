<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo8emyggg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jo8emyggg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-arrow-out-down-right" /></template>
