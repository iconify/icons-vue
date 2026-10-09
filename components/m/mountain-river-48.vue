<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx5i_8glh.css';
import '../../css/u/uyhqdeb9l.css';
import '../../css/u/ua2_qkbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sx5i_8glh"/><path class="uyhqdeb9l"/><path class="ua2_qkbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mountain-river-48" /></template>
