<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9ekdu1_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9ekdu1_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:market-analysis" /></template>
