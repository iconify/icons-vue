<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l_u0y7e4h.css';
import '../../css/u/u729wwm-w.css';
import '../../css/t/tkc2gdazg.css';
import '../../css/c/cvwjuk0bx.css';
import '../../css/m/mk7_fccwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l_u0y7e4h wm-k"/><path class="u729wwm-w wm-a"/><path class="tkc2gdazg wm-shadow"/><path class="cvwjuk0bx wm-k"/><path class="mk7_fccwz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:thumbs-up-engrave" /></template>
