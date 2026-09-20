<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p69es9xsi.css';
import '../../css/o/oi7oh5xgv.css';
import '../../css/u/umm_x8b-p.css';
import '../../css/a/aeyxu9b2r.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGZb8TIcFs"><g class="ft5dv1b6b"><path class="p69es9xsi"/><path class="oi7oh5xgv"/><path clip-rule="evenodd" class="umm_x8b-p"/><path class="aeyxu9b2r"/></g></mask></defs><path mask="url(#SVGZb8TIcFs)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:view-horizont-duotone" /></template>
