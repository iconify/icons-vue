<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/o/oi14-thur.css';
import '../../css/b/b3j6u1bxs.css';
import '../../css/a/a4fcd752j.css';
import '../../css/z/zm14bkbwk.css';
import '../../css/p/phhdeybqm.css';
import '../../css/b/by_q2slgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="oi14-thur"/><path class="b3j6u1bxs"/><path class="a4fcd752j"/><path class="zm14bkbwk"/><path class="phhdeybqm"/><path class="by_q2slgr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:youtube-logo" /></template>
