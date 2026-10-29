<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/n-pg4abef.css';
import '../../css/q/qxcyf63hh.css';
import '../../css/n/nz0tn9b7v.css';
import '../../css/v/vqpslccme.css';
import '../../css/f/fkn1-guxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="n-pg4abef wm-k"/><path class="qxcyf63hh wm-s"/><path class="nz0tn9b7v wm-shadow"/><path class="vqpslccme wm-k"/><path class="fkn1-guxf wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-pen-engrave" /></template>
