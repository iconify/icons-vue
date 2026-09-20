<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr9sd8b1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yr9sd8b1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:papermc-paper-light" /></template>
