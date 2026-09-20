<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifuftsm3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifuftsm3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sim-off-outline" /></template>
