<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m93uw9bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m93uw9bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:x-circle-fill-24" /></template>
