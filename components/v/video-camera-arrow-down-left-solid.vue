<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmguok5nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rmguok5nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:video-camera-arrow-down-left-solid" /></template>
