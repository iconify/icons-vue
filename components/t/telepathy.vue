<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozd69z-yo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ozd69z-yo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:telepathy" /></template>
