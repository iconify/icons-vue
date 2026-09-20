<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfx_zmbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bfx_zmbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:willow-light" /></template>
