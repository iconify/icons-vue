<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zcdue44-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zcdue44-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:metal-boot" /></template>
