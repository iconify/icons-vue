<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hbzdspbjk.css';
import '../../css/r/razfpcbqg.css';
import '../../css/w/wjakhsbqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hbzdspbjk"/><path class="razfpcbqg"/><path class="wjakhsbqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-sketch" /></template>
