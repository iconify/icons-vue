<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/favheljet.css';
import '../../css/r/r90zuab0u.css';
import '../../css/u/u_1ogdcfb.css';
import '../../css/b/bbkvi1b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="favheljet wm-k"/><path class="r90zuab0u wm-a"/><path class="u_1ogdcfb wm-k"/><path class="bbkvi1b5u wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:maximize-sketch" /></template>
