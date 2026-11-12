<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cua72wbew.css';
import '../../css/h/hsd7tzbla.css';
import '../../css/k/kbi-vfbsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cua72wbew"/><path class="hsd7tzbla"/><path class="kbi-vfbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:qdrant-dark" /></template>
