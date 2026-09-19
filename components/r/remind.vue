<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/va0qzx95a.css';
import '../../css/i/ie-ns4b3y.css';
import '../../css/z/z0u1g-tdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="va0qzx95a"/><path class="ie-ns4b3y"/><path class="z0u1g-tdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:remind" /></template>
