<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq8d756sd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dq8d756sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:video-camera-off-filled" /></template>
