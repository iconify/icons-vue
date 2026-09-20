<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppy3-er_s.css';
import '../../css/n/nbc91yb5f.css';
import '../../css/w/wgnfdbbso.css';
import '../../css/f/f253fb81r.css';
import '../../css/x/x3o_a1byi.css';
import '../../css/o/oji2ps6ab.css';
import '../../css/b/b58cght7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":171};
const content = `<defs><linearGradient id="SVGYeLhubCc" x1="13.878%" x2="89.144%" y1="55.934%" y2="58.694%"><stop offset="0%" class="ppy3-er_s"/><stop offset="40%" class="ppy3-er_s"/><stop offset="83%" class="nbc91yb5f"/><stop offset="100%" class="wgnfdbbso"/></linearGradient><linearGradient id="SVGll66Sdsg" x1="54.315%" x2="54.315%" y1="82.782%" y2="39.307%"><stop offset="0%" class="wgnfdbbso"/><stop offset="100%" class="f253fb81r"/></linearGradient></defs><path class="x3o_a1byi"/><path fill="url(#SVGYeLhubCc)" class="oji2ps6ab"/><path fill="url(#SVGll66Sdsg)" class="b58cght7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:meta" /></template>
