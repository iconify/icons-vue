<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne6g2k11l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ne6g2k11l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mechanic-garage" /></template>
