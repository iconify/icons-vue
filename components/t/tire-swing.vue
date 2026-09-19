<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/y/yl6j-sw3a.css';
import '../../css/w/w46zwovhm.css';
import '../../css/f/fb_cx8b6e.css';
import '../../css/z/zk8wz60ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="yl6j-sw3a"/><ellipse class="w46zwovhm"/><ellipse class="fb_cx8b6e"/><path class="zk8wz60ql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:tire-swing" /></template>
