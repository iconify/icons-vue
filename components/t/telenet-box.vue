<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4m_ima2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4m_ima2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:telenet-box" /></template>
