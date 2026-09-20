<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie8p9lh6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ie8p9lh6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:photo-camera-cancelled" /></template>
