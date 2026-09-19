<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/v/vkcj4bcdm.css';
import '../../css/x/xedfj89fl.css';
import '../../css/c/cfsfyeb-n.css';
import '../../css/m/mdc3ss7xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="vkcj4bcdm"/><path class="xedfj89fl"/><path class="cfsfyeb-n"/><path class="mdc3ss7xx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:music-cd" /></template>
