<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c01x__lky.css';
import '../../css/e/eiiamhb2z.css';
import '../../css/v/v_r-dov2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c01x__lky"/><path class="eiiamhb2z"/><path class="v_r-dov2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:play-stream-line-duotone" /></template>
