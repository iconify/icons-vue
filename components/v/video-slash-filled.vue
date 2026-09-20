<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h0jv6pbln.css';
import '../../css/f/fab031bju.css';
import '../../css/b/bwtd6wb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h0jv6pbln"/><path class="fab031bju"/><path class="bwtd6wb2e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-slash-filled" /></template>
