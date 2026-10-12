<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bmv2fpbdp.css';
import '../../css/j/jtt_i7b8h.css';
import '../../css/p/pdnbnwbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bmv2fpbdp"/><path class="jtt_i7b8h"/><path class="pdnbnwbzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:notebook-text-duotone" /></template>
