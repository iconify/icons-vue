<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tz3uhdcoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tz3uhdcoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:right-arrow-1" /></template>
