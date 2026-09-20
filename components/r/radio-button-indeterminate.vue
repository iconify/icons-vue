<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fclsd1b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fclsd1b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:radio-button-indeterminate" /></template>
