<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qi45swhau.css';
import '../../css/h/hol78yygl.css';
import '../../css/h/hpmok1bvn.css';
import '../../css/n/ncb32vbdb.css';
import '../../css/y/yq2xhabuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="qi45swhau"/><path class="hol78yygl"/><path clip-rule="evenodd" class="hpmok1bvn"/><path class="ncb32vbdb"/><path class="yq2xhabuf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:person-vampire" /></template>
