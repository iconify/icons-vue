<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up1479bcz.css';
import '../../css/n/nxbjncgfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="up1479bcz"/><path class="nxbjncgfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:zoom-in" /></template>
