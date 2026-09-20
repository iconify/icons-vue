<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpsm7jb6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kpsm7jb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:webcam-video-solid" /></template>
