<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4fy3wbjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x4fy3wbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-15-seconds-forward-outline" /></template>
