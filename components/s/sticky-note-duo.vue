<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lv90sjbvj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vyks3abws.css';
import '../../css/r/ryc81jbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv90sjbvj secondary"/><g class="dt0cm9dhy primary"><path class="vyks3abws"/><path class="ryc81jbwe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:sticky-note-duo" /></template>
