<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt43jbb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="yt43jbb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pause" /></template>
