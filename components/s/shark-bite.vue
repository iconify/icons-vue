<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwk70sbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qwk70sbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shark-bite" /></template>
