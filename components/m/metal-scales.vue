<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlbqq21ap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wlbqq21ap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:metal-scales" /></template>
