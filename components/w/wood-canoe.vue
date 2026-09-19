<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trutf_b7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="trutf_b7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wood-canoe" /></template>
