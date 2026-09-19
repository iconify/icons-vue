<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzgeh0v4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bzgeh0v4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:media-play" /></template>
