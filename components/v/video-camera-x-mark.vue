<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w02oomkub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w02oomkub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:video-camera-x-mark" /></template>
