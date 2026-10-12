<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e3s5wzb5x.css';
import '../../css/o/o9eo1e7xa.css';
import '../../css/v/v-0f67bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="e3s5wzb5x"/><path class="o9eo1e7xa"/><path class="v-0f67bvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:send-duotone" /></template>
