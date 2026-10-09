<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghgrl9bnl.css';
import '../../css/q/qcs6rdphe.css';
import '../../css/x/xpp-7oufq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ghgrl9bnl"/><path class="qcs6rdphe"/><path class="xpp-7oufq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:offshore-platform-48-bold" /></template>
