<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smi-2nbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="smi-2nbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:refresh-circle-1-clockwise" /></template>
