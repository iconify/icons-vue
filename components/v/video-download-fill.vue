<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xahzi_p2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xahzi_p2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:video-download-fill" /></template>
