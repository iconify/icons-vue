<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/grhn4x43p.css';
import '../../css/q/q4qupqb4k.css';
import '../../css/f/fipq_j4gc.css';
import '../../css/k/kz59c3b1j.css';
import '../../css/x/x8zkwfbgu.css';
import '../../css/a/au_aybbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="grhn4x43p wm-k"/><path class="q4qupqb4k wm-s"/><path class="fipq_j4gc wm-k"/><circle class="kz59c3b1j wm-a"/><path class="wm-a x8zkwfbgu"/><circle class="au_aybbmf wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:usb-sketch" /></template>
