<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l-fwh23rz.css';
import '../../css/w/wxy7qktvt.css';
import '../../css/e/ekgo0ibnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l-fwh23rz"/><path class="wxy7qktvt"/><path class="ekgo0ibnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:smartphone-charging-duotone" /></template>
