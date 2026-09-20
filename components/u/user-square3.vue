<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/s/stfrz6bje.css';
import '../../css/n/nwyzuufrs.css';
import '../../css/f/flmf6fbyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="stfrz6bje"/><path class="nwyzuufrs"/><path class="flmf6fbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:user-square3" /></template>
