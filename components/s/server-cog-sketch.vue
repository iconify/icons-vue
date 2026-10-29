<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nrmp6jb4l.css';
import '../../css/o/ogqc83-ym.css';
import '../../css/e/eknhatjjm.css';
import '../../css/g/go4bf3bjm.css';
import '../../css/p/pbt1s1b_f.css';
import '../../css/c/cjwt2qmii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nrmp6jb4l"/><path class="ogqc83-ym wm-k"/><path class="eknhatjjm wm-a"/><path class="go4bf3bjm wm-k"/><path class="pbt1s1b_f wm-a"/><path class="cjwt2qmii wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:server-cog-sketch" /></template>
