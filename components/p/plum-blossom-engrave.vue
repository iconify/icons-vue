<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dg0zgsbkz.css';
import '../../css/f/fj14r_biv.css';
import '../../css/a/aia4wcpia.css';
import '../../css/h/hjxvjzbmm.css';
import '../../css/a/a-ykpnb1v.css';
import '../../css/v/v5gb87bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dg0zgsbkz wm-k"/><path class="fj14r_biv wm-a"/><path class="aia4wcpia wm-shadow"/><path class="hjxvjzbmm wm-k"/><path class="a-ykpnb1v wm-s"/><path class="v5gb87bbj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:plum-blossom-engrave" /></template>
