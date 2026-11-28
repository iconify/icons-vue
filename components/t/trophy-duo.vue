<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksntg5bby.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i59-8zbak.css';
import '../../css/u/uz85sjvru.css';
import '../../css/a/a6vtm2nyb.css';
import '../../css/m/memn3xbdy.css';
import '../../css/c/c4zkbo2em.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksntg5bby secondary"/><g class="dt0cm9dhy primary"><path class="i59-8zbak"/><path class="uz85sjvru"/><path class="a6vtm2nyb"/><path class="memn3xbdy"/><path class="c4zkbo2em"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:trophy-duo" /></template>
