<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ab6o8pbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ab6o8pbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:xing" /></template>
