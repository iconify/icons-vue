<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/s/snheepb0e.css';
import '../../css/w/wv_hmvbsw.css';
import '../../css/i/iwealhp1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="snheepb0e"/><path class="wv_hmvbsw"/><path class="iwealhp1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:upload" /></template>
