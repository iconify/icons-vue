<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/civkr7bau.css';
import '../../css/h/hs38sub6q.css';
import '../../css/l/l9lv5_bcf.css';
import '../../css/l/l0v-b4kbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="civkr7bau"/><path class="hs38sub6q wm-a"/><path class="l9lv5_bcf"/><path class="l0v-b4kbr wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scan-text-duo" /></template>
