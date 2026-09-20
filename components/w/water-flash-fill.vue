<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcc_rg86w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcc_rg86w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:water-flash-fill" /></template>
