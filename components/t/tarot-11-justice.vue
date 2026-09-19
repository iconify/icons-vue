<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zia8pjbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zia8pjbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-11-justice" /></template>
