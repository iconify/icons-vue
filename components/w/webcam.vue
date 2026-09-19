<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9ynb3b_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i9ynb3b_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:webcam" /></template>
