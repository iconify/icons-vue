<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1zlj_b8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":384};
const content = `<path class="k1zlj_b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:view-comfy" /></template>
