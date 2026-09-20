<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzi166bfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vzi166bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tiktok-light" /></template>
