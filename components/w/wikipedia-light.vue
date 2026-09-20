<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1hgjccdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y1hgjccdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wikipedia-light" /></template>
