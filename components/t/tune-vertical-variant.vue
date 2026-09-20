<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4fzgdc_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4fzgdc_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tune-vertical-variant" /></template>
