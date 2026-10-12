<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g4xm99bgk.css';
import '../../css/x/xz0npwbkb.css';
import '../../css/q/q_atanv8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g4xm99bgk"/><path class="xz0npwbkb"/><path class="q_atanv8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:spotlight-duotone" /></template>
