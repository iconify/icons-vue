<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdk9h-bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdk9h-bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:paintbrush" /></template>
