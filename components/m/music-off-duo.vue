<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iercfls4x.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zxmc7xb9t.css';
import '../../css/y/yi37gdbko.css';
import '../../css/s/sqy0bqbaa.css';
import '../../css/q/qjzyurbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iercfls4x secondary"/><g class="dt0cm9dhy primary"><path class="zxmc7xb9t"/><path class="yi37gdbko"/><path class="sqy0bqbaa"/><path class="qjzyurbpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:music-off-duo" /></template>
