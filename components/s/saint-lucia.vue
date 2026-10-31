<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5ultbcim.css';
import '../../css/c/cpvfcjbza.css';
import '../../css/j/jy3omdbnr.css';
import '../../css/h/hq2cko65l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="w5ultbcim"/><path class="cpvfcjbza"/><path class="jy3omdbnr"/><path class="hq2cko65l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:saint-lucia" /></template>
