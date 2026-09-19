<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxbe2vbtu.css';
import '../../css/j/jk7vrq09y.css';
import '../../css/z/ziq40nb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fxbe2vbtu"/><path class="jk7vrq09y"/><path class="ziq40nb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:note" /></template>
