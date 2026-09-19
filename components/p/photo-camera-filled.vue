<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0n7kkb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0n7kkb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:photo-camera-filled" /></template>
