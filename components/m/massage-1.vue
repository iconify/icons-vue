<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm9xzf3xr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dm9xzf3xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:massage-1" /></template>
