<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcosn_gan.css';
import '../../css/p/pnxir5bod.css';
import '../../css/c/c20deubpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qcosn_gan"/><path class="pnxir5bod"/><path class="c20deubpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:steel-mill-48-bold" /></template>
