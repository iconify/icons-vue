<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd4d16bdk.css';
import '../../css/s/saqgotbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gd4d16bdk"/><path class="saqgotbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:upload-cloud-20" /></template>
