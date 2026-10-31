<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_d9wxb8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_d9wxb8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wind-turbine-fill-round" /></template>
