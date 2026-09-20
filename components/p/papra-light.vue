<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy4g9dohn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fy4g9dohn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papra-light" /></template>
