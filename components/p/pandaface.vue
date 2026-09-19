<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/par4x9bhq.css';
import '../../css/i/ivsg4dbkt.css';
import '../../css/r/ryz94svvw.css';
import '../../css/f/fg1y5-srt.css';
import '../../css/p/p572u4buk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="par4x9bhq"/><path class="ivsg4dbkt"/><path class="ryz94svvw"/><path class="fg1y5-srt"/><path class="p572u4buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:pandaface" /></template>
