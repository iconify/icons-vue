<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyz8g5qxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fyz8g5qxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yahoo-dark" /></template>
