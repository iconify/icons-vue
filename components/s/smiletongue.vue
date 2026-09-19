<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7269db2g.css';
import '../../css/l/lmrf6zs5l.css';
import '../../css/y/y1ig9vb1s.css';
import '../../css/s/s92dlccok.css';
import '../../css/p/pxpgiw7hy.css';
import '../../css/w/wegr_lbpd.css';
import '../../css/i/igopaeb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i7269db2g"/><path class="lmrf6zs5l"/><path class="y1ig9vb1s"/><path class="s92dlccok"/><path class="pxpgiw7hy"/><path class="wegr_lbpd"/><path class="igopaeb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:smiletongue" /></template>
