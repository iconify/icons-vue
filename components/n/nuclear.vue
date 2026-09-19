<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq8fi23ln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xq8fi23ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:nuclear" /></template>
