<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yes_z39me.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yes_z39me"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:romm-snes-light" /></template>
