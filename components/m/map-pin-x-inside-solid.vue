<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnf2_ub3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnf2_ub3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:map-pin-x-inside-solid" /></template>
