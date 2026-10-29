<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q4kgunb4a.css';
import '../../css/t/t_nt3d-cv.css';
import '../../css/i/iwi6igpcd.css';
import '../../css/u/uyqfuvpqv.css';
import '../../css/p/ppl-__b6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q4kgunb4a"/><path class="t_nt3d-cv wm-k"/><path class="iwi6igpcd wm-k"/><path class="uyqfuvpqv wm-a"/><path class="ppl-__b6i wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:smartphone-message-sketch" /></template>
