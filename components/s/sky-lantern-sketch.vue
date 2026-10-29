<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uvbus5bkk.css';
import '../../css/c/c-lvbj2xn.css';
import '../../css/b/bk_2j6bja.css';
import '../../css/k/kxrlzfb-u.css';
import '../../css/u/ugk7yrm0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uvbus5bkk"/><path class="c-lvbj2xn wm-k"/><path class="bk_2j6bja wm-a"/><path class="kxrlzfb-u wm-k"/><path class="ugk7yrm0d wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sky-lantern-sketch" /></template>
