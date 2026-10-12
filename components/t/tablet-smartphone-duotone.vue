<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qz5i1miti.css';
import '../../css/o/o5_vxlb_k.css';
import '../../css/t/t5gmhdcyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qz5i1miti"/><path class="o5_vxlb_k"/><path class="t5gmhdcyl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tablet-smartphone-duotone" /></template>
