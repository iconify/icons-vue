<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lfims1-zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lfims1-zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:terror" /></template>
