<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rsnxk8bsw.css';
import '../../css/m/mkvoqhbvr.css';
import '../../css/b/bk_g8t1yc.css';
import '../../css/t/tm1vapb3d.css';
import '../../css/w/wtpwdyb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="rsnxk8bsw"/><path class="mkvoqhbvr"/><path class="bk_g8t1yc"/><path class="tm1vapb3d"/><path class="wtpwdyb5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:qr-code-scan" /></template>
