<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqsa_mblk.css';
import '../../css/c/cx1y_wb5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qqsa_mblk"/><path class="cx1y_wb5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:proxmox" /></template>
