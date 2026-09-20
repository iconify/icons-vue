<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtkvdwb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtkvdwb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:trae" /></template>
