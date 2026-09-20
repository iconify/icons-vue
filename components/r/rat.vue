<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-gk5toyn.css';
import '../../css/u/u7nu2pb9k.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/f/fjcp8ybpo.css';
import '../../css/h/h-a276n1c.css';
import '../../css/o/oxfx_zbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="s-gk5toyn"/><path class="u7nu2pb9k"/><g class="jn8qy4bru"><path class="fjcp8ybpo"/><path class="h-a276n1c"/><path class="oxfx_zbyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:rat" /></template>
