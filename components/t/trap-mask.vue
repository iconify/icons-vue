<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfmq1ggwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qfmq1ggwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trap-mask" /></template>
