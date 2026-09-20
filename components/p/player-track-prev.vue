<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdpwa7bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdpwa7bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:player-track-prev" /></template>
