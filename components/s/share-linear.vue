<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/at_81ebpk.css';
import '../../css/b/bqfg75b4w.css';
import '../../css/g/gz3zbhgyq.css';
import '../../css/i/iyvfpqslp.css';
import '../../css/b/bz9hxnbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="at_81ebpk"/><path class="bqfg75b4w"/><path class="gz3zbhgyq"/><path class="iyvfpqslp"/><path class="bz9hxnbeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:share-linear" /></template>
