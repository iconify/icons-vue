<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/t/tu4qdd9vm.css';
import '../../css/l/lnotn3pcn.css';
import '../../css/r/r-m4ambab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="tu4qdd9vm"/><path class="lnotn3pcn"/><circle class="r-m4ambab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:sleep-two" /></template>
