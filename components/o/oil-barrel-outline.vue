<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpgb8bbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpgb8bbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:oil-barrel-outline" /></template>
