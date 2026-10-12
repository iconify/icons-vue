<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/ly71s_b6w.css';
import '../../css/o/ok5vfptqt.css';
import '../../css/l/l1m86fbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ly71s_b6w"/><path class="ok5vfptqt"/><path class="l1m86fbpq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:soap-dispenser-droplet-duotone" /></template>
