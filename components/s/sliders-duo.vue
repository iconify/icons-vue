<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6hm_cznf.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vt_vge82q.css';
import '../../css/h/h3x0v4biq.css';
import '../../css/l/l0aldw27v.css';
import '../../css/v/v1j-mbbje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6hm_cznf secondary"/><g class="dt0cm9dhy primary"><path class="vt_vge82q"/><circle class="h3x0v4biq"/><path class="l0aldw27v"/><circle class="v1j-mbbje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sliders-duo" /></template>
