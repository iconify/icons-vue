<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/h-brjibpa.css';
import '../../css/s/s-28vgayl.css';
import '../../css/d/d1wudil8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="h-brjibpa"/><path class="s-28vgayl"/><path class="d1wudil8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-top-open-linear" /></template>
