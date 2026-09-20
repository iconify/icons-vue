<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wxnndwbls.css';
import '../../css/x/xz7p6tbng.css';
import '../../css/s/s0trtnb1m.css';
import '../../css/z/zhintvt7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wxnndwbls"/><path class="xz7p6tbng"/><path class="s0trtnb1m"/><path class="zhintvt7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:video-games-device-switch-joy-controller" /></template>
