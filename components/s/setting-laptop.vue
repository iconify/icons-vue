<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/k/kbesibb3g.css';
import '../../css/h/h1tke7swh.css';
import '../../css/x/x2401pk9v.css';
import '../../css/g/g6li1jbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="kbesibb3g"/><path class="h1tke7swh"/><circle class="x2401pk9v"/><path class="g6li1jbuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:setting-laptop" /></template>
