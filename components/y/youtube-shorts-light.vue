<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwa_69bpz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mwa_69bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:youtube-shorts-light" /></template>
