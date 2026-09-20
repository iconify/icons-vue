<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jktt-zflc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jktt-zflc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:thermometer-line" /></template>
