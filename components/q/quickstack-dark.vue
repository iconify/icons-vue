<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa8qgofrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pa8qgofrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:quickstack-dark" /></template>
