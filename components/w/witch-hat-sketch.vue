<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l1ig0xbpa.css';
import '../../css/h/hqwworbnp.css';
import '../../css/o/ocp2bcc9q.css';
import '../../css/v/v2uh4zbrq.css';
import '../../css/j/jjp9km4pf.css';
import '../../css/y/y4zjjxbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l1ig0xbpa"/><path class="hqwworbnp wm-k"/><path class="ocp2bcc9q wm-a"/><path class="v2uh4zbrq wm-k"/><path class="jjp9km4pf wm-a"/><path class="wm-s y4zjjxbox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:witch-hat-sketch" /></template>
