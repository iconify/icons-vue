<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1xiqqxwq.css';
import '../../css/u/uiavscbxc.css';
import '../../css/p/p_qrzz42h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="m1xiqqxwq"/><path class="uiavscbxc"/><path class="p_qrzz42h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:pakistan" /></template>
