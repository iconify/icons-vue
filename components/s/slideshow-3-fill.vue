<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3hd5ph4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3hd5ph4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:slideshow-3-fill" /></template>
