<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr9d0ie7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gr9d0ie7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:video-camera-fill" /></template>
