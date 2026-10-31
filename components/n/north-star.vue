<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exwrc0-ch.css';
import '../../css/s/s40yd4vsw.css';
import '../../css/m/mt5na0h5u.css';
import '../../css/l/l9ra1ma2i.css';
import '../../css/t/t3olyhrta.css';
import '../../css/t/tajnr1btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="exwrc0-ch"><path class="s40yd4vsw wm-shadow"/><path class="mt5na0h5u wm-shadow"/><path class="l9ra1ma2i wm-shadow"/><path class="t3olyhrta wm-a"/><path class="tajnr1btw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:north-star" /></template>
