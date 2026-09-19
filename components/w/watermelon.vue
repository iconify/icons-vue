<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/a/alx19_r_t.css';
import '../../css/s/sewd1ccmo.css';
import '../../css/f/f3thebb2v.css';
import '../../css/l/lz2098e2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="alx19_r_t"/><path class="sewd1ccmo"/><path class="f3thebb2v"/><path class="lz2098e2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:watermelon" /></template>
