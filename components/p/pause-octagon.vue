<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_2dj1b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_2dj1b3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pause-octagon" /></template>
