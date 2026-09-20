<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stlwhqbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="stlwhqbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:video-edit-slow-motion" /></template>
