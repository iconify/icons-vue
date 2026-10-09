<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfao_6b1t.css';
import '../../css/q/qepjo_bej.css';
import '../../css/t/t9qz5obke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rfao_6b1t"/><path class="qepjo_bej"/><path class="t9qz5obke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tractor-48-bold" /></template>
