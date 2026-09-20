<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_ivevbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_ivevbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:open-source-hardware" /></template>
