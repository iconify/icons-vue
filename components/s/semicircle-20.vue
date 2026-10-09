<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_si_y0xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m_si_y0xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:semicircle-20" /></template>
