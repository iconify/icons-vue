<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq-hce4iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fq-hce4iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:video-cut" /></template>
