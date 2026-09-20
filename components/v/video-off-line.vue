<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbh-7tfuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbh-7tfuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:video-off-line" /></template>
