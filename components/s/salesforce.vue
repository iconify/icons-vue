<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpga_ecty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpga_ecty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:salesforce" /></template>
