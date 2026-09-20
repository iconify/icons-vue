<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/b/bou9xbwdh.css';
import '../../css/p/pntbjgyyc.css';
import '../../css/i/iycln-b8i.css';
import '../../css/w/wxsfzjbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGq2TPJcdC" x1="80.361" x2="442.399" y1="-452.399" y2="-90.361" gradientTransform="matrix(1 0 0 -1 -5.38 -15.38)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="0" class="bou9xbwdh"/><stop offset="1" class="pntbjgyyc"/></linearGradient><circle fill="url(#SVGq2TPJcdC)" class="iycln-b8i"/><path class="wxsfzjbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:photoprism" /></template>
