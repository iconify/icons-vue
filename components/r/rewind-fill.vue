<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yo9q5npwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo9q5npwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rewind-fill" /></template>
