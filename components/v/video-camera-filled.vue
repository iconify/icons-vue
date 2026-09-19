<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm_rohcmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cm_rohcmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:video-camera-filled" /></template>
