<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1hd5ebhz.css';
import '../../css/l/lyd-xwqcp.css';
import '../../css/n/ndnl__jzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p1hd5ebhz"/><path class="lyd-xwqcp"/><path class="ndnl__jzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-annotation-toggle" /></template>
