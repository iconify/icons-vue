<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msnn70bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msnn70bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:staples-outline-24px" /></template>
