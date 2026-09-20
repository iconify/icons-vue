<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6w23hbvq.css';
import '../../css/l/luh2gib-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f6w23hbvq"/><path class="luh2gib-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rancher-desktop" /></template>
