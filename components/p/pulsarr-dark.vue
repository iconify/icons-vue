<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg089kb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tg089kb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pulsarr-dark" /></template>
