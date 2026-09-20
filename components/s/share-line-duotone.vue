<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/at_81ebpk.css';
import '../../css/b/bqfg75b4w.css';
import '../../css/g/gz3zbhgyq.css';
import '../../css/g/gb8649bzx.css';
import '../../css/s/su3mifb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="at_81ebpk"/><path class="bqfg75b4w"/><path class="gz3zbhgyq"/><path class="gb8649bzx"/><path class="su3mifb4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:share-line-duotone" /></template>
