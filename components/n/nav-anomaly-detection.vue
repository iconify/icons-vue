<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik8j_0m_s.css';
import '../../css/l/lm0uu894d.css';
import '../../css/i/iltdgbc8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ik8j_0m_s"/><path class="lm0uu894d"/><path class="iltdgbc8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-anomaly-detection" /></template>
