<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrbn05bgs.css';
import '../../css/b/boo849bbg.css';
import '../../css/z/zf2mmcbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrbn05bgs"/><path class="boo849bbg"/><path class="zf2mmcbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:sitemap" /></template>
