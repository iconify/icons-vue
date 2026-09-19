<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbm03u4xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="kbm03u4xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:wieght" /></template>
