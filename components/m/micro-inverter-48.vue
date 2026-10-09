<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsgp-8odn.css';
import '../../css/u/unq7cxbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xsgp-8odn"/><path class="unq7cxbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:micro-inverter-48" /></template>
