<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cp5tmibid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cp5tmibid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tv2-play-light" /></template>
