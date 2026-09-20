<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8oo7gb6g.css';
import '../../css/c/c0sioac0q.css';
import '../../css/l/lqp2b9btq.css';
import '../../css/l/lh2z7ynqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="c0sioac0q"/><path class="lqp2b9btq"/><path class="lh2z7ynqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:wallet" /></template>
