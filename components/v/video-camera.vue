<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba8lzwb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ba8lzwb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:video-camera" /></template>
