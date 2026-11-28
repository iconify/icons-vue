<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sp4y2o2dy.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qk02rk5oc.css';
import '../../css/l/l6k4qhb5r.css';
import '../../css/o/on25g_baf.css';
import '../../css/i/icgal8prs.css';
import '../../css/d/du1e6ebuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary sp4y2o2dy"/><g class="dt0cm9dhy primary"><path class="qk02rk5oc"/><path class="l6k4qhb5r"/><path class="on25g_baf"/><path class="icgal8prs"/><path class="du1e6ebuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:robot-duo" /></template>
