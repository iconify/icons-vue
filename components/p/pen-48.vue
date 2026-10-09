<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo64yvbkk.css';
import '../../css/g/gsxa1w5va.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xo64yvbkk"/><path class="gsxa1w5va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pen-48" /></template>
