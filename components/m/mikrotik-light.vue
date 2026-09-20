<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhd9kmzpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jhd9kmzpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mikrotik-light" /></template>
