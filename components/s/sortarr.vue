<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgoppccno.css';
import '../../css/o/o-pdocb-v.css';
import '../../css/k/ka00n71yt.css';
import '../../css/v/vkyxbikjz.css';
import '../../css/d/d8xyog2ir.css';
import '../../css/k/kcg9zbb9s.css';
import '../../css/b/bkg5-s3_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<radialGradient id="SVGkDsnFbHG" cx="-702.128" cy="799.197" r="1.085" gradientTransform="matrix(0 320 320 0 -255487 224885)" gradientUnits="userSpaceOnUse"><stop offset="0" class="lgoppccno"/><stop offset="1" class="o-pdocb-v"/></radialGradient><circle fill="url(#SVGkDsnFbHG)" class="ka00n71yt"/><path class="vkyxbikjz"/><path class="d8xyog2ir"/><path class="kcg9zbb9s"/><path class="bkg5-s3_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:sortarr" /></template>
