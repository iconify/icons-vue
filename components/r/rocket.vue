<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/m/mev3yvbte.css';
import '../../css/k/k3ne98vfh.css';
import '../../css/a/ayameacfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(4 1)" class="jtowsomii"><path class="mev3yvbte"/><path class="k3ne98vfh"/><circle class="ayameacfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:rocket" /></template>
