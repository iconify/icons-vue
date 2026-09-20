<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omjv7encm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="omjv7encm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:visa" /></template>
