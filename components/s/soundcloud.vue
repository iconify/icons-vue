<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n_h5odf9q.css';
import '../../css/n/nn5-jrewn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGG2vCAb8C)" class="n_h5odf9q"/><defs><linearGradient id="SVGG2vCAb8C" x1="30064.2" x2="30064.2" y1="507.299" y2="18096.6" gradientUnits="userSpaceOnUse"><stop class="nn5-jrewn"/><stop offset="1" class="nn5-jrewn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:soundcloud" /></template>
