<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgj5w8hcw.css';
import '../../css/v/vd-zhbsrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wgj5w8hcw"/><path class="vd-zhbsrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rupee-48-bold" /></template>
