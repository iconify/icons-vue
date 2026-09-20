<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/icfm9_b4l.css';
import '../../css/b/bkbdjkb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="icfm9_b4l"/><path clip-rule="evenodd" class="bkbdjkb8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:map-marker-area" /></template>
