<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxfrv-bud.css';
import '../../css/n/nw12yw8jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gxfrv-bud"/><path class="nw12yw8jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:wave-height" /></template>
