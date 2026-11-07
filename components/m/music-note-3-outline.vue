<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgut2ibqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sgut2ibqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-3-outline" /></template>
