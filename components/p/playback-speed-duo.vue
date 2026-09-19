<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bba6s1bkv.css';
import '../../css/j/jfns5ihsk.css';
import '../../css/w/w-klkw3bj.css';
import '../../css/r/rn6_kx1aa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="bba6s1bkv"/><path class="jfns5ihsk"/><path class="w-klkw3bj"/><path class="rn6_kx1aa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:playback-speed-duo" /></template>
