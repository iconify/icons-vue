<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xqnihhblm.css';
import '../../css/x/xn7199bdf.css';
import '../../css/w/whhjun3cu.css';
import '../../css/n/nz2tvdblu.css';
import '../../css/h/hfmoz1dvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="xqnihhblm"/><path class="xn7199bdf"/><path class="whhjun3cu"/><path class="nz2tvdblu"/><path class="hfmoz1dvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:video-camera" /></template>
