<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/u/ufx_3tb7d.css';
import '../../css/o/omlm7pxxb.css';
import '../../css/p/pil4o0bhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(3 4)" class="jtowsomii"><circle class="ufx_3tb7d"/><path class="omlm7pxxb"/><path class="pil4o0bhx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:toggles" /></template>
