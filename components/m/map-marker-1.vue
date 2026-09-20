<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atti1kbuc.css';
import '../../css/w/w57s-x_gs.css';
import '../../css/r/rkutulbsh.css';
import '../../css/q/qzguk0yob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="atti1kbuc"/><path clip-rule="evenodd" class="w57s-x_gs"/><path class="rkutulbsh"/><path class="qzguk0yob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:map-marker-1" /></template>
