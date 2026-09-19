<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm7o1er_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dm7o1er_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:threeraysleft" /></template>
