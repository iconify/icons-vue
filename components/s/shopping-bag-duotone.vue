<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rg3c-hb8r.css';
import '../../css/q/qbkn2frqz.css';
import '../../css/d/d2hyv4llv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rg3c-hb8r"/><path class="qbkn2frqz"/><path class="d2hyv4llv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shopping-bag-duotone" /></template>
