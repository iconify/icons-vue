<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf2mm_--c.css';
import '../../css/k/kr_fs7b3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tf2mm_--c"/><path class="kr_fs7b3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pickaxe-48" /></template>
