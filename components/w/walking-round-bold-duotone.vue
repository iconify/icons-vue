<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_scq114p.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/e/ed016ybbg.css';
import '../../css/y/yswxml9zk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_scq114p"/><g class="xtpeb-edw"><path class="ed016ybbg"/><path class="yswxml9zk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:walking-round-bold-duotone" /></template>
