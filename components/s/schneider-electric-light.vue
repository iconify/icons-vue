<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tp8o9vbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tp8o9vbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:schneider-electric-light" /></template>
