<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8oo7gb6g.css';
import '../../css/w/w7lfhmbwk.css';
import '../../css/p/pard6diuc.css';
import '../../css/k/kou1ambby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="w7lfhmbwk"/><path class="pard6diuc"/><path class="kou1ambby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:package-alt-2" /></template>
