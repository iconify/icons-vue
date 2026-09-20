<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c98y_fk5b.css';
import '../../css/v/vc--wpv5i.css';
import '../../css/w/wsvgiff-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGgUnW0cXV" x1="20.449" x2="398.46" y1="491.551" y2="113.54" gradientUnits="userSpaceOnUse"><stop offset="0" class="c98y_fk5b"/><stop offset="1" class="vc--wpv5i"/></linearGradient><path fill="url(#SVGgUnW0cXV)" class="wsvgiff-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:swetrix-light" /></template>
