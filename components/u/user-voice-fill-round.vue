<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2a8hqbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2a8hqbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-voice-fill-round" /></template>
