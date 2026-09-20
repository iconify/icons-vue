<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvp56kb_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qvp56kb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:romm-snes-dark" /></template>
