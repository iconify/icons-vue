<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_-k83bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_-k83bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-arrow-right-linear" /></template>
