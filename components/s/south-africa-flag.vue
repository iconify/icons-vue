<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkyw1x0bs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nkyw1x0bs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:south-africa-flag" /></template>
