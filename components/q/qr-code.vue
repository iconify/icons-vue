<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-3n4tbkv.css';
import '../../css/h/htf9mo5im.css';
import '../../css/a/aeqfr4vbi.css';
import '../../css/p/p9_zic3jl.css';
import '../../css/d/dqiqyxalr.css';
import '../../css/b/bfxy05bvr.css';
import '../../css/n/nb4051b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b-3n4tbkv"/><path class="htf9mo5im"/><path class="aeqfr4vbi"/><path class="p9_zic3jl"/><path class="dqiqyxalr"/><path class="bfxy05bvr"/><path class="nb4051b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:qr-code" /></template>
