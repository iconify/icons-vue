<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npc39g6la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="npc39g6la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:shopping-security" /></template>
