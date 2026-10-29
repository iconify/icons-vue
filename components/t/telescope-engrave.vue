<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b1ccms0_q.css';
import '../../css/j/jwh4a8b9j.css';
import '../../css/j/juth7gb_k.css';
import '../../css/k/kbj8nvb7i.css';
import '../../css/p/ptk50absq.css';
import '../../css/n/nboiatbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b1ccms0_q wm-k"/><path class="jwh4a8b9j wm-a"/><path class="juth7gb_k wm-shadow"/><path class="kbj8nvb7i wm-k"/><path class="ptk50absq wm-k"/><path class="nboiatbai wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:telescope-engrave" /></template>
