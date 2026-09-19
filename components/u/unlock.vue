<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/j/j9vg3_jgc.css';
import '../../css/s/skrettb2q.css';
import '../../css/h/hmcoah3hh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><rect class="j9vg3_jgc"/><path class="skrettb2q"/><path class="hmcoah3hh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:unlock" /></template>
