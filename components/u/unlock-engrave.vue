<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ap5h-cbhb.css';
import '../../css/l/llefpiban.css';
import '../../css/f/fvgc87o3c.css';
import '../../css/w/wbk6h5rku.css';
import '../../css/b/b86buo32x.css';
import '../../css/k/ki55z6ilg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ap5h-cbhb wm-k"/><path class="llefpiban wm-a"/><path class="fvgc87o3c wm-shadow"/><path class="wbk6h5rku wm-a"/><path class="b86buo32x wm-k"/><path class="ki55z6ilg wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:unlock-engrave" /></template>
