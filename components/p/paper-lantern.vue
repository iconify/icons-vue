<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku0_1_nkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ku0_1_nkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:paper-lantern" /></template>
