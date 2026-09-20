<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fluw8rpzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fluw8rpzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:spinner" /></template>
