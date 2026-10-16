<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq_kneo0b.css';
import '../../css/i/i-510_b_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vq_kneo0b"/><path class="i-510_b_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spillway-48" /></template>
