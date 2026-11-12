<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-ul83bfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n-ul83bfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:radarr-anime-dark" /></template>
