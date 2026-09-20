<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw1tzdbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nw1tzdbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:teamviewer-dark" /></template>
