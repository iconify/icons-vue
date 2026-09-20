<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-wkamaxf.css';
import '../../css/f/f24w92bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a-wkamaxf"/><path class="f24w92bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:radarr" /></template>
