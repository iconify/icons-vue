<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8_xspb3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="t8_xspb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:video-camera" /></template>
