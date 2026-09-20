<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2mpopbcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="k2mpopbcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:panel-sectioned" /></template>
