<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/vom9q9u4u.css';
import '../../css/q/q8390zcod.css';
import '../../css/v/vl8q6rbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="vom9q9u4u"/><path class="q8390zcod"/><path class="vl8q6rbbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:rate-stretch-tool" /></template>
