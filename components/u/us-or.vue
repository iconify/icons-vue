<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/n/nnfv0rblz.css';
import '../../css/n/nb67_53zj.css';
import '../../css/w/wwcnv88rc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="nnfv0rblz"/><path class="nb67_53zj"/><path class="wwcnv88rc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:us-or" /></template>
