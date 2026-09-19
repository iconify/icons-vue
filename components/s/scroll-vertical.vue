<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_dp74riv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_dp74riv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:scroll-vertical" /></template>
