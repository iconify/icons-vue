<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kfxsxib_c.css';
import '../../css/b/bh9ehm6bl.css';
import '../../css/f/fdl6i8bpk.css';
import '../../css/j/j2ywqub6x.css';
import '../../css/q/qs0kxmvmt.css';
import '../../css/v/v-787n_1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kfxsxib_c wm-k"/><path class="bh9ehm6bl wm-a"/><path class="fdl6i8bpk wm-shadow"/><path class="j2ywqub6x wm-k"/><path class="qs0kxmvmt wm-k"/><path class="v-787n_1k wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wreath-engrave" /></template>
