<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9djg6bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g9djg6bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plex-rewind-light" /></template>
