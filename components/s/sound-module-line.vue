<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7k3eshrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7k3eshrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sound-module-line" /></template>
