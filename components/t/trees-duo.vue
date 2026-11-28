<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw-k-3lxs.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/q9vqqg3uc.css';
import '../../css/i/ind7lkbgs.css';
import '../../css/u/u0k_e_b5k.css';
import '../../css/s/swkiuumwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw-k-3lxs secondary"/><g class="dt0cm9dhy primary"><path class="q9vqqg3uc"/><path class="ind7lkbgs"/><path class="u0k_e_b5k"/><path class="swkiuumwe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:trees-duo" /></template>
