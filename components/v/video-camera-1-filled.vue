<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/df3f3o36e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df3f3o36e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:video-camera-1-filled" /></template>
