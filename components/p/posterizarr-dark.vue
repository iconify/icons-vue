<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0dmoy_jy.css';
import '../../css/z/zpx94h-bl.css';
import '../../css/y/yiook0b5l.css';
import '../../css/i/io-vn9b5p.css';
import '../../css/s/swdohebjr.css';
import '../../css/z/zqdwlbpai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f0dmoy_jy"/><path class="zpx94h-bl"/><path class="yiook0b5l"/><path class="io-vn9b5p"/><path class="swdohebjr"/><path class="zqdwlbpai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:posterizarr-dark" /></template>
