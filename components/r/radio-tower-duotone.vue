<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/io_d464_v.css';
import '../../css/d/d33c5cfcb.css';
import '../../css/t/t3i4ct49o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="io_d464_v"/><path class="d33c5cfcb"/><path class="t3i4ct49o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:radio-tower-duotone" /></template>
