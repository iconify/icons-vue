<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nw5ws-b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nw5ws-b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uruky-dark" /></template>
