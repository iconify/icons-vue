<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jd-spsilb.css';
import '../../css/o/od6cmr_8o.css';
import '../../css/v/vp7gs9big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jd-spsilb"/><path class="od6cmr_8o"/><path class="vp7gs9big"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:shovel-duotone" /></template>
