<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rrjakbcym.css';
import '../../css/a/a6ca1bcxc.css';
import '../../css/e/epyd8hb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rrjakbcym"/><path class="a6ca1bcxc"/><path class="epyd8hb_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:ui-phone-slider-vertical" /></template>
