<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc1fd0lxe.css';
import '../../css/x/xh7ixbc7w.css';
import '../../css/j/jjy93ib8m.css';
import '../../css/a/a0a4fku7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="xh7ixbc7w"/><path class="jjy93ib8m"/><path class="a0a4fku7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circle-flags:mq" /></template>
