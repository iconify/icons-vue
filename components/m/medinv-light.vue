<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh8ic0_ra.css';
import '../../css/x/xtvx8sn3q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zh8ic0_ra"/><circle class="xtvx8sn3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:medinv-light" /></template>
