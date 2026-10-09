<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-pfn5jar.css';
import '../../css/l/lq1s_sbrc.css';
import '../../css/v/vhowmnhvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u-pfn5jar"/><path class="lq1s_sbrc"/><path class="vhowmnhvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:zoom-in-48-bold" /></template>
