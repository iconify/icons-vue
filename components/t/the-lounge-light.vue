<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-gphv0ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s-gphv0ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:the-lounge-light" /></template>
