<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwq5s_bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwq5s_bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pool-electric-lvl" /></template>
