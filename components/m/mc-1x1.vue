<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv9qcacyl.css';
import '../../css/k/krvb6vbdu.css';
import '../../css/d/d79ru3bml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="nv9qcacyl"><path class="krvb6vbdu"/><path class="d79ru3bml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:mc-1x1" /></template>
