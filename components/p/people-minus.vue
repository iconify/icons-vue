<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sg600_1ny.css';
import '../../css/g/g8xngh9xv.css';
import '../../css/i/ic9ebcqwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="sg600_1ny"/><path clip-rule="evenodd" class="g8xngh9xv"/><path class="ic9ebcqwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:people-minus" /></template>
