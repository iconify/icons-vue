<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou-qwlbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou-qwlbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:video-fill" /></template>
