<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pm6orv45l.css';
import '../../css/w/wpycjcc8p.css';
import '../../css/f/fs1i-xbzv.css';
import '../../css/q/qj9lcp8az.css';
import '../../css/b/b4_iq75ad.css';
import '../../css/y/ymd90j6dp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="pm6orv45l"/><path clip-rule="evenodd" class="wpycjcc8p"/><rect class="fs1i-xbzv"/><path clip-rule="evenodd" class="qj9lcp8az"/><rect class="b4_iq75ad"/><path class="ymd90j6dp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:robot" /></template>
