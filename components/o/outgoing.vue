<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/i/ism4d7bfy.css';
import '../../css/t/t1l8wac3t.css';
import '../../css/i/iucmbeysh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ism4d7bfy"/><path class="t1l8wac3t"/><path class="iucmbeysh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:outgoing" /></template>
