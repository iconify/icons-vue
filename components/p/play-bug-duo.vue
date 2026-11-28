<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk1iapbhj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vbe8lbbcp.css';
import '../../css/t/t3i5tcbhl.css';
import '../../css/e/ekp9r-bkm.css';
import '../../css/u/u8lek1bgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary sk1iapbhj"/><g class="dt0cm9dhy primary"><path class="vbe8lbbcp"/><path class="t3i5tcbhl"/><path class="ekp9r-bkm"/><path class="u8lek1bgr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:play-bug-duo" /></template>
