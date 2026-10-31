<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w05t1cbam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w05t1cbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:voicemail-duocolor-round" /></template>
