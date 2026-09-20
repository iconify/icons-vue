<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6f1imrlb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6f1imrlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:video-frame-cut-bold" /></template>
