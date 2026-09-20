<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aljiy_w3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aljiy_w3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tv2-play-dark" /></template>
