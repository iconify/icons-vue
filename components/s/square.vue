<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mme__qbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mme__qbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:square" /></template>
