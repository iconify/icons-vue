<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/r/rct529mqu.css';
import '../../css/h/hqz31-bnt.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/o/oh4f1hbmh.css';
import '../../css/z/zpu53zwhs.css';
import '../../css/b/bochahbmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="rct529mqu wm-deco"/><path class="hqz31-bnt wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="oh4f1hbmh wm-k"/><path class="wm-a zpu53zwhs"/><path class="bochahbmj wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scan-face-blueprint" /></template>
