<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgbcv7b_q.css';
import '../../css/n/n8l508bll.css';
import '../../css/o/oq_hyob2z.css';
import '../../css/j/ji2pwab3q.css';
import '../../css/y/yb-927bwx.css';
import '../../css/n/nqkhm47fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><radialGradient id="SVGUc3xce1Z" cx="84" cy="67.4" r="118.7" gradientUnits="userSpaceOnUse"><stop offset="0" class="lgbcv7b_q"/><stop offset=".85" class="n8l508bll"/><stop offset="1" class="n8l508bll"/></radialGradient></defs><path class="oq_hyob2z"/><path fill="url(#SVGUc3xce1Z)" transform="matrix(3 0 0 3 -52.11 -23.26)" class="ji2pwab3q"/><path class="yb-927bwx"/><path class="nqkhm47fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="xero-emoji:splatter" /></template>
