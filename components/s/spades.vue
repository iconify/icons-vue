<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue4dxlbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue4dxlbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:spades" /></template>
