<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et_wnkuox.css';
import '../../css/w/wqhrjbcye.css';
import '../../css/q/qdytrdbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="et_wnkuox"/><path class="wqhrjbcye"/><path class="qdytrdbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-inverter-check-48" /></template>
