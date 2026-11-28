<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbhk-2bhh.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/n3heq6b6w.css';
import '../../css/i/ip-lweb_e.css';
import '../../css/j/jmt_hp8qh.css';
import '../../css/q/qj4rgrb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbhk-2bhh secondary"/><g class="dt0cm9dhy primary"><path class="n3heq6b6w"/><path class="ip-lweb_e"/><path class="jmt_hp8qh"/><path class="qj4rgrb1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:teacher-duo" /></template>
