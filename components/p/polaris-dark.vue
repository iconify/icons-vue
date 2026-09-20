<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0sdl1bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s0sdl1bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:polaris-dark" /></template>
