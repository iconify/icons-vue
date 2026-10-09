<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsqrtwbgr.css';
import '../../css/m/mycvpqjmo.css';
import '../../css/e/eia-tm77s.css';
import '../../css/f/fd646mbuc.css';
import '../../css/e/ehc07rbtk.css';
import '../../css/s/sah4z2bjx.css';
import '../../css/i/izmfm5jxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jsqrtwbgr"/><path class="mycvpqjmo"/><path class="eia-tm77s"/><path class="fd646mbuc"/><path class="ehc07rbtk"/><path class="sah4z2bjx"/><path class="izmfm5jxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-panel-x-20-bold" /></template>
