<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a397vwbha.css';
import '../../css/t/t0x-i1v4p.css';
import '../../css/f/f5ysqvu5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a397vwbha"/><path class="t0x-i1v4p"/><path class="f5ysqvu5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:notebook-pen-duotone" /></template>
