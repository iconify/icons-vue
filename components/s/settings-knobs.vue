<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rupycd98g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rupycd98g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:settings-knobs" /></template>
