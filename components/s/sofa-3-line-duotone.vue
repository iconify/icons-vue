<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xic0yhb9p.css';
import '../../css/l/lbt5_vw5t.css';
import '../../css/t/tqcxtn8zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xic0yhb9p"/><path class="lbt5_vw5t"/><path class="tqcxtn8zv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sofa-3-line-duotone" /></template>
