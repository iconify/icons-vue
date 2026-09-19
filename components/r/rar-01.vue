<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlparkbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlparkbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rar-01" /></template>
