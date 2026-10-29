<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/knwu_bb7f.css';
import '../../css/g/gv5pdcc_f.css';
import '../../css/k/ko2u7ibee.css';
import '../../css/l/l9lv5_bcf.css';
import '../../css/m/mujhne3lv.css';
import '../../css/v/vjpnyegoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="knwu_bb7f wm-k"/><path class="gv5pdcc_f wm-a"/><path class="ko2u7ibee wm-shadow"/><path class="l9lv5_bcf wm-k"/><path class="mujhne3lv wm-a"/><path class="vjpnyegoq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scan-eye-engrave" /></template>
