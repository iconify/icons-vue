<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b07l858kq.css';
import '../../css/z/zc8gt6bcb.css';
import '../../css/o/olz2vxb5s.css';
import '../../css/x/xmczdvb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="b07l858kq"/><path clip-rule="evenodd" class="zc8gt6bcb"/><path class="olz2vxb5s"/><path clip-rule="evenodd" class="xmczdvb2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:modulo-outline" /></template>
