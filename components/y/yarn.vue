<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/denkpb94f.css';
import '../../css/o/ouq9fewiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="denkpb94f"/><path class="ouq9fewiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:yarn" /></template>
