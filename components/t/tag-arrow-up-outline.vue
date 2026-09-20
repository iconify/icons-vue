<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v92wobbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v92wobbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-arrow-up-outline" /></template>
