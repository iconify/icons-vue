<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aw96d85ov.css';
import '../../css/i/i1_yy39iv.css';
import '../../css/a/agaffo5ho.css';
import '../../css/p/pmviisk7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aw96d85ov"/><path class="i1_yy39iv"/><path class="agaffo5ho"/><path class="pmviisk7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mine-water-20-bold" /></template>
