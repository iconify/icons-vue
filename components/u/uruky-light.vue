<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcu6ucb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mcu6ucb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uruky-light" /></template>
