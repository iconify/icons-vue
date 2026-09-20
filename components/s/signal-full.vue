<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_hbxdkvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="m_hbxdkvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:signal-full" /></template>
