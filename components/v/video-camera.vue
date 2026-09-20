<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w19i0ospy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w19i0ospy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:video-camera" /></template>
