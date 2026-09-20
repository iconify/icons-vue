<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m23vo5mck.css';
import '../../css/s/s70b2cb2s.css';
import '../../css/r/rsy4chbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m23vo5mck"/><path class="s70b2cb2s"/><path class="rsy4chbta"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:town" /></template>
