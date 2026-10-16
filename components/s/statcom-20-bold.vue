<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qoecip_zs.css';
import '../../css/u/u-2khd52i.css';
import '../../css/v/vysp5-ryk.css';
import '../../css/o/oheu1iy3h.css';
import '../../css/t/tspxr7b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qoecip_zs"/><path class="u-2khd52i"/><path class="vysp5-ryk"/><path class="oheu1iy3h"/><path class="tspxr7b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:statcom-20-bold" /></template>
