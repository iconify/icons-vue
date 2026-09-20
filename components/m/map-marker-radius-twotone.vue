<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwx3pl.css';
import '../../css/y/ydovum.css';
import '../../css/u/ucrnen.css';
import '../../css/u/uy8cjk.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-42.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';
import '../../css/d/d-zdr4ap.css';
import '../../css/d/d-1z8qst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwx3pl ydovum"/><circle class="ucrnen ydovum"/><path class="uy8cjk ydovum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:map-marker-radius-twotone" /></template>
