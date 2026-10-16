<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhd-y3l3p.css';
import '../../css/u/uconxdb5j.css';
import '../../css/k/kmsu02uqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xhd-y3l3p"/><path class="uconxdb5j"/><path class="kmsu02uqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:synchronous-condenser-48" /></template>
