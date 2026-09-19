<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xqznafu2t.css';
import '../../css/s/s2rco2s5i.css';
import '../../css/g/g5bfogrxx.css';
import '../../css/q/q5y5tebdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xqznafu2t"/><path class="s2rco2s5i"/><path class="g5bfogrxx"/><path class="q5y5tebdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:trulli" /></template>
