<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaa9xgbbh.css';
import '../../css/q/q_br50bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jaa9xgbbh"/><path class="q_br50bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:safari" /></template>
