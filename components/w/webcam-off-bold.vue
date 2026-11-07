<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4xvgmwrd.css';
import '../../css/h/hedfj8jjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v4xvgmwrd"/><path class="hedfj8jjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:webcam-off-bold" /></template>
