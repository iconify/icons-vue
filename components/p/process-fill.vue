<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_d-36btl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_d-36btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:process-fill" /></template>
