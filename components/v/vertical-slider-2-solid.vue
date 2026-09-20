<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihj4t_b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ihj4t_b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:vertical-slider-2-solid" /></template>
