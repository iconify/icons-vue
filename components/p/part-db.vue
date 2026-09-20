<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pa8h15bym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pa8h15bym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:part-db" /></template>
