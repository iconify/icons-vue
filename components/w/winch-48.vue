<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6h-ysber.css';
import '../../css/k/kxtdmfuan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c6h-ysber"/><path class="kxtdmfuan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:winch-48" /></template>
