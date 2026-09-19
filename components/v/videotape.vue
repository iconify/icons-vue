<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/x/xlntljo_b.css';
import '../../css/y/y58k7bb-w.css';
import '../../css/c/cke3tihzk.css';
import '../../css/v/vs4rimaky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xlntljo_b"/><circle class="y58k7bb-w"/><circle class="cke3tihzk"/><path class="vs4rimaky"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:videotape" /></template>
