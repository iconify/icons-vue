<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgd8jygye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rgd8jygye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:telephonereceiver2" /></template>
