<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tym57sy9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2.5};
const content = `<path class="tym57sy9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:video-camera-vintage-f" /></template>
