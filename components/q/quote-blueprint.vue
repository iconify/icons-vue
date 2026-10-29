<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/z/zqi7n5vpo.css';
import '../../css/a/av5roibzc.css';
import '../../css/m/mhdr543mh.css';
import '../../css/k/kzy2krb6a.css';
import '../../css/z/ziv0n64rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco zqi7n5vpo"/><path class="av5roibzc wm-deco"/><path class="mhdr543mh wm-deco"/><path class="kzy2krb6a"/><path class="ziv0n64rr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:quote-blueprint" /></template>
