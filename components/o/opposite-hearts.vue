<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmlzksx2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cmlzksx2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:opposite-hearts" /></template>
