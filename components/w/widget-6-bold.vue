<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wui8tcbyn.css';
import '../../css/k/kh6yd2nhl.css';
import '../../css/i/i_vz0301x.css';
import '../../css/z/ziyj3ibvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wui8tcbyn"/><path class="kh6yd2nhl"/><path class="i_vz0301x"/><path class="ziyj3ibvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:widget-6-bold" /></template>
