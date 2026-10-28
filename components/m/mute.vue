<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i55-vdeam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i55-vdeam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:mute" /></template>
