<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccv974_1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccv974_1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:swap-horizontal-bold" /></template>
