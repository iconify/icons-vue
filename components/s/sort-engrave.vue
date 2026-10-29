<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rnol45y_o.css';
import '../../css/a/a4hjggb0v.css';
import '../../css/k/k_zyttb9q.css';
import '../../css/z/zmx3w_bje.css';
import '../../css/l/lof7i1b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rnol45y_o wm-k"/><path class="a4hjggb0v wm-a"/><path class="k_zyttb9q wm-shadow"/><path class="wm-k zmx3w_bje"/><path class="lof7i1b0v wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sort-engrave" /></template>
