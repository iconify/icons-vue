<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/poyl9bqjz.css';
import '../../css/l/ld6jjrbyc.css';
import '../../css/q/q9s3y8uha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="poyl9bqjz"/><circle class="ld6jjrbyc"/><path class="q9s3y8uha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:waistline" /></template>
