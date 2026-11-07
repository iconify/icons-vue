<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/iy-deskju.css';
import '../../css/l/l2mia0a0a.css';
import '../../css/j/jlzhyksrr.css';
import '../../css/y/yjjibyi4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iy-deskju"/><path class="l2mia0a0a"/><path class="jlzhyksrr"/><path class="yjjibyi4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reorder-2-line-duotone" /></template>
