<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0gifg4or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0gifg4or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-frame2-filled" /></template>
