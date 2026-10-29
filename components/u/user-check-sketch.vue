<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/r-0p0fbzi.css';
import '../../css/j/j6mk4rb0u.css';
import '../../css/b/bg_4nf-bb.css';
import '../../css/p/p5gauvcbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="r-0p0fbzi"/><path class="j6mk4rb0u wm-k"/><path class="bg_4nf-bb wm-k"/><path class="p5gauvcbg wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-check-sketch" /></template>
