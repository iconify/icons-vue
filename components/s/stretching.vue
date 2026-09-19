<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/rvl8hqvnj.css';
import '../../css/q/qhb4jfb5g.css';
import '../../css/q/qhtreac6e.css';
import '../../css/r/rf7rbhbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="rvl8hqvnj"/><path class="qhb4jfb5g"/><path class="qhtreac6e"/><path class="rf7rbhbsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:stretching" /></template>
