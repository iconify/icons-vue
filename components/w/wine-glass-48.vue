<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wry8nmbpn.css';
import '../../css/c/crnolnb_i.css';
import '../../css/l/lak7f2bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wry8nmbpn"/><path class="crnolnb_i"/><path class="lak7f2bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wine-glass-48" /></template>
