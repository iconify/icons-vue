<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6an7pvvv.css';
import '../../css/b/b17e7nbsz.css';
import '../../css/u/uyd0dabdt.css';
import '../../css/o/ocywhlbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u6an7pvvv"/><path class="b17e7nbsz"/><path class="uyd0dabdt"/><path class="ocywhlbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-battery-48" /></template>
