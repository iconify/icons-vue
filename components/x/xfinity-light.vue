<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9754coca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p9754coca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xfinity-light" /></template>
