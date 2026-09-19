<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ips20vbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ips20vbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:triangle-solid" /></template>
