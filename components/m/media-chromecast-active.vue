<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8h5gaujn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s8h5gaujn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-chromecast-active" /></template>
