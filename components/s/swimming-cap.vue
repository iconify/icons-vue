<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/adc0nobix.css';
import '../../css/y/yxfi3h8at.css';
import '../../css/p/pxbmlybch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="adc0nobix"/><path class="yxfi3h8at"/><path class="pxbmlybch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:swimming-cap" /></template>
