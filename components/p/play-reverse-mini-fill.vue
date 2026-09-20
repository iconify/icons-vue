<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb_juvaxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb_juvaxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:play-reverse-mini-fill" /></template>
