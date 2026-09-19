<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhi296bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dhi296bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:parachute" /></template>
