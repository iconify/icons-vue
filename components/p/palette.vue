<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibpb4ib8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ibpb4ib8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:palette" /></template>
