<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq5iey98t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq5iey98t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:trello-fill" /></template>
