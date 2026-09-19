<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pgwf7peyp.css';
import '../../css/m/mi3accbzy.css';
import '../../css/b/bnczibbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pgwf7peyp"/><path class="mi3accbzy"/><path class="bnczibbir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:presentation-04" /></template>
