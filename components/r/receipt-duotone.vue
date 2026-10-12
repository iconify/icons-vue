<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ew_pm7bud.css';
import '../../css/c/c5mar1biz.css';
import '../../css/g/g48c9l9px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ew_pm7bud"/><path class="c5mar1biz"/><path class="g48c9l9px"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:receipt-duotone" /></template>
