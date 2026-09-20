<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chko4obfw.css';
import '../../css/m/m3xop7dba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chko4obfw"/><path class="m3xop7dba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:palette-3-line" /></template>
