<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_0bqujjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u_0bqujjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-3-outline" /></template>
