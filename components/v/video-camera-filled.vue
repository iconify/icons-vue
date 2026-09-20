<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w404mpg1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="w404mpg1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:video-camera-filled" /></template>
