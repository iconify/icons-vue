<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/i/i6jo9jcep.css';
import '../../css/b/bxximwbyx.css';
import '../../css/m/mv-hq9vel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i6jo9jcep"/><path class="bxximwbyx"/><path class="mv-hq9vel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:material-and-texture" /></template>
