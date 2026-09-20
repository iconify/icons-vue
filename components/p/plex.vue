<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wckuc9nmc.css';
import '../../css/h/hze02wt4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="wckuc9nmc"/><path class="hze02wt4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plex" /></template>
