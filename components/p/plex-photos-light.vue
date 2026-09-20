<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dygj92bzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dygj92bzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:plex-photos-light" /></template>
