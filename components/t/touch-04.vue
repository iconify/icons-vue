<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oun3kebky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oun3kebky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:touch-04" /></template>
