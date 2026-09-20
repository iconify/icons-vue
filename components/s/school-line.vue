<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2y0ofppi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2y0ofppi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:school-line" /></template>
