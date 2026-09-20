<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfge6sb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pfge6sb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:photo-camera-cancelled-filled" /></template>
