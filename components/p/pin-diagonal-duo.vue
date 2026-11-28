<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_j2c6bga.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jlkcm4hst.css';
import '../../css/n/nkc-s7b_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_j2c6bga secondary"/><g class="dt0cm9dhy primary"><path class="jlkcm4hst"/><path class="nkc-s7b_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pin-diagonal-duo" /></template>
