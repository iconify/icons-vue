<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/a5-ljbc1k.css';
import '../../css/e/el2i0p4-i.css';
import '../../css/h/h3y64vb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="a5-ljbc1k"/><path class="el2i0p4-i wm-shadow"/><path class="h3y64vb5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:power-engrave" /></template>
