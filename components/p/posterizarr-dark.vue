<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0dmoy_jy.css';
import '../../css/n/nto6dua-r.css';
import '../../css/q/qdk_35dda.css';
import '../../css/a/ax-9p8b4q.css';
import '../../css/a/a9unhdbjq.css';
import '../../css/u/uii6-7_ty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f0dmoy_jy"/><path class="nto6dua-r"/><path class="qdk_35dda"/><path class="ax-9p8b4q"/><path class="a9unhdbjq"/><path class="uii6-7_ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:posterizarr-dark" /></template>
