<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/is7p6owsa.css';
import '../../css/q/q6bv9r6nh.css';
import '../../css/f/fq06eqbqz.css';
import '../../css/l/ljeitrr-k.css';
import '../../css/o/oe4c91bbg.css';
import '../../css/v/vmhlk0o_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="is7p6owsa wm-k"/><path class="q6bv9r6nh wm-s"/><path class="fq06eqbqz wm-shadow"/><path class="ljeitrr-k wm-k"/><path class="oe4c91bbg wm-s"/><path class="vmhlk0o_i wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-clock-engrave" /></template>
