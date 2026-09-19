<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k7245g1tp.css';
import '../../css/z/zvafccczm.css';
import '../../css/m/mq5xx16sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect class="k7245g1tp"/><path class="zvafccczm"/><rect transform="rotate(90 15 29)" class="mq5xx16sw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:painted-screen" /></template>
