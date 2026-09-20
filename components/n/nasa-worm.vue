<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivehy_b5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ivehy_b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nasa-worm" /></template>
