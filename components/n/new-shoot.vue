<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkcgv_1ff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tkcgv_1ff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:new-shoot" /></template>
