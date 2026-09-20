<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrgb9jblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrgb9jblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:video-edit-magic-wand" /></template>
