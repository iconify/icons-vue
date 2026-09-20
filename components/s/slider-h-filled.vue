<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9fr5jbox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9fr5jbox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:slider-h-filled" /></template>
