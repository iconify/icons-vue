<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/moruyr3gw.css';
import '../../css/s/sunmddcgj.css';
import '../../css/c/c0m8i--rf.css';
import '../../css/p/pty22pbyc.css';
import '../../css/n/nengl2b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="moruyr3gw"/><path class="sunmddcgj"/><circle class="c0m8i--rf"/><circle class="pty22pbyc"/><circle class="nengl2b3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:pear" /></template>
