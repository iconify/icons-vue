<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk1hxdbxp.css';
import '../../css/v/vfx4m_b5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wk1hxdbxp"/><path class="vfx4m_b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phase-shifter-48" /></template>
