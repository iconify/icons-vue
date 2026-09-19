<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czw74fo5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="czw74fo5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:orb-direction" /></template>
