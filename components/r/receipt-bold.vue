<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_u2lacwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_u2lacwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:receipt-bold" /></template>
