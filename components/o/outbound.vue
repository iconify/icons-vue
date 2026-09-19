<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/mjczpwbmh.css';
import '../../css/l/lenqly58b.css';
import '../../css/h/h79q5vbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="mjczpwbmh"/><circle class="lenqly58b"/><path class="h79q5vbot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:outbound" /></template>
