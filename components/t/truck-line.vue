<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nn5c_ac-c.css';
import '../../css/a/a71n0cp7w.css';
import '../../css/n/nvedv7b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nn5c_ac-c"/><path class="a71n0cp7w"/><path class="nvedv7b7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:truck-line" /></template>
