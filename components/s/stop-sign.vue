<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij2x_72vy.css';
import '../../css/k/k1g07dbri.css';
import '../../css/x/xku__bb_n.css';
import '../../css/j/j15hc4biq.css';
import '../../css/s/sc6lftqsd.css';
import '../../css/y/y0oqz1bau.css';
import '../../css/h/hpcdq09vd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="ij2x_72vy"><path class="k1g07dbri"/><path class="xku__bb_n"/></g><path class="j15hc4biq"/><path class="sc6lftqsd"/><path class="y0oqz1bau"/><path class="hpcdq09vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:stop-sign" /></template>
