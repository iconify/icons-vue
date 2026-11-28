<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tws2_vbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tws2_vbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:syringe-check" /></template>
