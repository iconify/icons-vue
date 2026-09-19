<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss2t-obao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":384};
const content = `<path class="ss2t-obao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:neg-1" /></template>
