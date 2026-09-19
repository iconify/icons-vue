<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrnvq_big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="qrnvq_big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:percent" /></template>
