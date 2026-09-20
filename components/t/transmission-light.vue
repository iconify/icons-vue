<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3rlzx3hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i3rlzx3hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:transmission-light" /></template>
