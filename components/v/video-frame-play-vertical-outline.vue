<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ded-w7bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ded-w7bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-play-vertical-outline" /></template>
