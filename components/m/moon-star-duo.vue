<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgzmasisn.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/o0fpmnz7u.css';
import '../../css/p/ph-o_tbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary sgzmasisn"/><g class="dt0cm9dhy primary"><path class="o0fpmnz7u"/><path class="ph-o_tbwq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:moon-star-duo" /></template>
