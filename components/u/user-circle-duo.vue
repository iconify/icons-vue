<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7rwnpxsz.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/u/u3sx6_b3g.css';
import '../../css/c/cej4cjp9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary z7rwnpxsz"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><circle class="u3sx6_b3g"/><path class="cej4cjp9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:user-circle-duo" /></template>
