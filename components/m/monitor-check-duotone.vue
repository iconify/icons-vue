<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yjlljib5h.css';
import '../../css/k/kx1bn5j4c.css';
import '../../css/o/o3yuhybec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yjlljib5h"/><path class="kx1bn5j4c"/><path class="o3yuhybec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-check-duotone" /></template>
