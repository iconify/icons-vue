<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygvaq_bgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ygvaq_bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:seven-of-bamboos-mahjong" /></template>
