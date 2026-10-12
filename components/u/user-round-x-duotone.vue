<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/laeq__ozm.css';
import '../../css/s/sf7yaz6nn.css';
import '../../css/o/okalx_bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="laeq__ozm"/><path class="sf7yaz6nn"/><path class="okalx_bvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-x-duotone" /></template>
