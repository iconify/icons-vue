<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/iz02l7bxj.css';
import '../../css/p/ptwz7cczz.css';
import '../../css/x/xohym5bkp.css';
import '../../css/c/c5_ce6b7b.css';
import '../../css/d/d7cftvo7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iz02l7bxj"/><path class="ptwz7cczz"/><path class="xohym5bkp"/><path class="c5_ce6b7b"/><path class="d7cftvo7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rubiks-cube" /></template>
