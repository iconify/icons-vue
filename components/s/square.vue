<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb8d45bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb8d45bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:square" /></template>
