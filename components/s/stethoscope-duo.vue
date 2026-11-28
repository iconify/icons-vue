<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9rwhn5xj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/ta6211bvx.css';
import '../../css/m/m53qvnbuy.css';
import '../../css/u/u4et_3yps.css';
import '../../css/x/x5vqjc9kw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary u9rwhn5xj"/><g class="dt0cm9dhy primary"><path class="ta6211bvx"/><path class="m53qvnbuy"/><path class="u4et_3yps"/><path class="x5vqjc9kw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stethoscope-duo" /></template>
