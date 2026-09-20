<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imv2uwbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imv2uwbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:maximize" /></template>
