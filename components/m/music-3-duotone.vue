<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s9psl9bzc.css';
import '../../css/m/m49r26bmi.css';
import '../../css/p/pf_z20b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s9psl9bzc"/><path class="m49r26bmi"/><path class="pf_z20b-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:music-3-duotone" /></template>
