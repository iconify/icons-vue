<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzfeosixy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzfeosixy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microphone-sparkle-fill-round" /></template>
