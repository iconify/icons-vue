<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq3_sibjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lq3_sibjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:tick-double" /></template>
