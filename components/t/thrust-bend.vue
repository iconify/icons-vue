<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmiy_hrng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xmiy_hrng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:thrust-bend" /></template>
