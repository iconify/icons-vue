<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp8a636dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gp8a636dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:planning-center-music-stand-light" /></template>
