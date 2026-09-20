<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csz2z-byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="csz2z-byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nordvpn-dark" /></template>
