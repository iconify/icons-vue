<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0hpm_bob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0hpm_bob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:music-note-1" /></template>
