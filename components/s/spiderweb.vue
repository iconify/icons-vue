<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl_4qt1zu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dl_4qt1zu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:spiderweb" /></template>
