<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd3rj95lz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd3rj95lz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:robotframework" /></template>
