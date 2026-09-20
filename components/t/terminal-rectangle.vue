<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/byhi3osvb.css';
import '../../css/g/gbfhxvenz.css';
import '../../css/w/wa-ouos2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="byhi3osvb"/><path class="gbfhxvenz"/><path class="wa-ouos2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:terminal-rectangle" /></template>
