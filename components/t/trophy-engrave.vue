<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hfap8z5lo.css';
import '../../css/p/pydtcwi0b.css';
import '../../css/p/pfzd08f0w.css';
import '../../css/r/ri984nurg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hfap8z5lo"/><path class="pydtcwi0b wm-shadow"/><path class="pfzd08f0w"/><path class="ri984nurg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:trophy-engrave" /></template>
