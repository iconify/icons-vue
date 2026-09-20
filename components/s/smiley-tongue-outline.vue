<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llqv21b5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llqv21b5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smiley-tongue-outline" /></template>
