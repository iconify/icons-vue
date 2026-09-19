<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzcl-4a-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fzcl-4a-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:star" /></template>
