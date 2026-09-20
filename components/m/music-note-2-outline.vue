<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb5qpacyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fb5qpacyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-2-outline" /></template>
