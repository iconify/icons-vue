<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xs3efil7b.css';
import '../../css/m/mmizfzbwi.css';
import '../../css/w/we9upfblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="xs3efil7b"/><path class="mmizfzbwi"/><path class="we9upfblt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sailboat" /></template>
