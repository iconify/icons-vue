<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tltd-smyd.css';
import '../../css/e/ehz_gxbyn.css';
import '../../css/j/jh5_0cbif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="tltd-smyd"/><path class="ehz_gxbyn wm-a"/><path class="jh5_0cbif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:speaker-duo" /></template>
