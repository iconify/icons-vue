<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/am8phpb_z.css';
import '../../css/l/lq2ck2bit.css';
import '../../css/k/k4f6kjbxw.css';
import '../../css/z/zt53swy0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="am8phpb_z"/><path class="lq2ck2bit"/><path class="k4f6kjbxw"/><path class="zt53swy0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:temperature-duo" /></template>
