<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-uyp2b0j.css';
import '../../css/q/qgl4r9bnu.css';
import '../../css/y/yf83rla5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u-uyp2b0j"/><path class="qgl4r9bnu"/><path class="yf83rla5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:penstock-48-bold" /></template>
