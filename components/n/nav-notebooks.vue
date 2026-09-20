<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am_4qubdp.css';
import '../../css/l/l70u19-fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="am_4qubdp"/><path class="l70u19-fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-notebooks" /></template>
