<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts_8b5bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ts_8b5bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:scroll-unfurled" /></template>
