<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t937w3bcg.css';
import '../../css/q/q6u6gfbgw.css';
import '../../css/g/gfo-qw48e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="t937w3bcg"/><path class="q6u6gfbgw"/><path class="gfo-qw48e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:success-picture" /></template>
