<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgc-kbc-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qgc-kbc-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:platform" /></template>
