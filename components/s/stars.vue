<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hsol5p2kz.css';
import '../../css/j/jy-0clbhq.css';
import '../../css/v/vlv50fa1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path class="hsol5p2kz"/><path class="jy-0clbhq"/><path class="vlv50fa1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:stars" /></template>
