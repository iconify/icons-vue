<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/j/j29qogbvy.css';
import '../../css/v/vqdqihuwl.css';
import '../../css/i/i7s2upniq.css';
import '../../css/l/lgsipkbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="j29qogbvy"/><path class="vqdqihuwl"/><path class="i7s2upniq"/><path class="lgsipkbuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:my" /></template>
