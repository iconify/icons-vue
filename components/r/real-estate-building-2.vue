<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bht69010r.css';
import '../../css/o/omuu71y8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bht69010r"/><path class="omuu71y8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:real-estate-building-2" /></template>
