<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-7-2mbbf.css';
import '../../css/l/lp5-n4bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u-7-2mbbf"/><path class="lp5-n4bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ticket-check-48-bold" /></template>
