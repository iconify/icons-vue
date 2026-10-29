<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pgggxhtzb.css';
import '../../css/r/rzoychbjy.css';
import '../../css/f/fmn_qacoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="pgggxhtzb"/><path class="rzoychbjy wm-a"/><path class="fmn_qacoy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ruler-duo" /></template>
