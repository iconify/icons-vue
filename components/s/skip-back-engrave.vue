<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/a0hdl5_si.css';
import '../../css/l/l1qckbbrk.css';
import '../../css/f/f82zt9l4a.css';
import '../../css/w/w3l25bb4w.css';
import '../../css/v/vjps6q3hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="a0hdl5_si wm-k"/><path class="l1qckbbrk wm-a"/><path class="f82zt9l4a wm-shadow"/><path class="w3l25bb4w wm-k"/><path class="vjps6q3hd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:skip-back-engrave" /></template>
